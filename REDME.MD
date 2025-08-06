# 🏥 Hospital Outpatient Management System (Microsoft Access)

This project is a simple yet functional **Hospital Outpatient Management System** built using **Microsoft Access**. It demonstrates key database concepts such as **table design, relationships, forms, queries, data validation,** and **report generation**.

---

## 📌 Features

- Two related tables: **Patients** and **Visits**
- Data validation rules (e.g., age range, required fields)
- Lookup combo box for gender and patient selection
- One-to-many relationship between Patients and Visits
- A user-friendly **form** for entering visit details
- A **report** generated from a query showing complete visit information
- Input mask for phone number formatting

---

## 🧱 Database Structure

### 🧑‍⚕️ Table: `Patients`

| Column Name     | Data Type     | Description                                |
|-----------------|---------------|--------------------------------------------|
| Patient_ID      | AutoNumber    | Primary Key (unique ID)                    |
| Patient_Name    | Short Text    | Required                                   |
| Gender          | Lookup Wizard | Options: Male, Female, Other               |
| Age             | Number        | Validation: Between 0 and 120              |
| PhoneNumber     | Short Text    | Input Mask: 10-digit format (e.g., 0000000000) |

### 📅 Table: `Visits`

| Column Name     | Data Type     | Description                                |
|-----------------|---------------|--------------------------------------------|
| Visit_ID        | AutoNumber    | Primary Key                                |
| VisitDate       | Date/Time     | Date of the visit                          |
| Doctor          | Short Text    | Required                                   |
| Patient_ID      | Number        | Foreign Key (linked to Patients table)     |

---

## 🔗 Relationships

- **One-to-Many** relationship from `Patients.Patient_ID` ➝ `Visits.Patient_ID`
- Enforced **referential integrity** to maintain data consistency

---

## 🧾 Queries

- `Visit_Details_Query`: Combines patient and visit data using a join
  - Includes: Patient Name, Doctor, Age, Phone Number, Visit Date

---

## 🧮 Forms

- **Visits Entry Form**: Pop-up style form for entering new visits  
  - Dropdown to select patient by name  
  - Automatically stores patient ID behind the scenes  

---

## 🖨️ Report

- Report created on the `Visit_Details_Query`
- Displays patient name, doctor, visit date, age, and phone number
- Useful for printing or reviewing outpatient records

---

## 💡 Technologies Used

- 💻 Microsoft Access 2016 or later
- 📊 MS Access Query Builder
- 🧩 Forms and Report Design tools

---

---

## 🧠 Learning Outcomes

- Designed relational tables with validation and constraints
- Built user-friendly forms and reports
- Learned how to work with lookup fields and input masks
- Understood one-to-many relationships in database design

---

## 📇 Author
Mohamatam Vyshnavi

---

