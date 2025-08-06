# 🏥 Hospital OPD Management System

The **Hospital OPD Management System** is a VBA-based automation project built using **Microsoft Excel**. It is designed to help streamline the operations of an Outpatient Department (OPD) by simplifying patient registration, appointment scheduling, and doctor allocation.

This system is ideal for small clinics, private hospitals, or training projects related to healthcare process automation.

---

## 📌 Key Features (Detailed Explanation)

### 1. 📝 Patient Registration
- A user-friendly form built using VBA allows staff to input new patient details.
- Captures key fields such as:
  - Full Name
  - Age and Gender
  - Contact Number
  - Visit Date
  - Reason for Visit
- Data is automatically saved in a structured Excel sheet (`Patient_Data`) for future access.

---

### 2. 📅 Appointment Scheduling
- Allows front-desk staff to book appointments for registered patients.
- Automatically prevents double-booking for the same doctor and time slot.
- Appointments are recorded along with patient ID and visit details.

---

### 3. 👨‍⚕️ Doctor Allocation
- Based on the patient’s reason for visit (e.g., fever, injury, etc.), the system assigns the patient to a relevant department and doctor.
- Doctor availability is cross-checked from the `Doctor_Schedule` sheet to ensure proper allocation.

---

### 4. 🔍 Search and Filter Functionality
- Staff can search for patients by:
  - Patient ID
  - Name
  - Appointment date
  - Assigned doctor
- Filters are implemented using Excel VBA to provide instant and dynamic search results.

---

### 5. 📊 Reporting Module
- Automatically generates reports for:
  - Daily visit counts
  - Weekly summary of patient appointments
  - Doctor-wise patient load
- Reports are displayed in tabular form and can be printed directly.

---

### 6. ✅ Data Validation & User Experience
- Drop-down lists are used for:
  - Gender selection
  - Department
  - Doctor names
- Validation rules prevent incomplete or incorrect data from being entered.
- Message boxes alert the user when fields are missing.

---

## 💻 Technologies Used

| Technology | Description |
|------------|-------------|
| Microsoft Excel | Main interface and database tables |
| VBA (Visual Basic for Applications) | Backend logic, automation, forms, buttons, reports |

---

## 🚀 How to Use

1. **Open Excel File**: Download and open `Hospital_OPD_Management_System.xlsm`.
2. **Enable Macros**: Click “Enable Content” when prompted to allow VBA execution.
3. **Navigate Through Dashboard**: Use buttons to access:
   - Register Patient Form
   - Schedule Appointment
   - Generate Reports
   - View Doctor Allocation
4. **Enter Data Using Forms**: All entries go through structured input forms.
5. **Review Reports**: Use the reports sheet for quick summaries.

---

