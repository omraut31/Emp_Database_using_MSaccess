# Employee Management System (MS Access + VBA)

This project is a comprehensive **Employee Management Database** developed using **Microsoft Access** and **VBA**. It provides a centralized system for managing employee profiles, banking details, departmental data, salary structures, and other related HR information.

## 🧰 Features

- **Employee Records Management**  
  Add, update, delete, and view employee profiles with ease.

- **Department & Bank Integration**  
  Dropdown menus for selecting predefined banks and departments linked via relational tables.

- **Photo Attachment**  
  Upload and store employee profile pictures within the database.

- **Salary Module**  
  - Capture base salary, taxable and non-taxable allowances  
  - Define salary periods (Monthly, Weekly, etc.)

- **User-Friendly Forms**  
  - Form-based GUI for record navigation (Add, Save, Delete, Next, Back)  
  - Detailed profile view with search functionality by `EmpID`

## 🗂️ Tables Used

- **Employee**  
  Stores all employee-related data including photo and salary details.

- **Banks**  
  Contains bank names, codes, branches, and a calculated branch serial.

- **Departments**  
  Stores department names used in dropdowns.

## 📌 Technologies

- Microsoft Access (Forms, Tables)
- VBA (For button logic, data binding, and navigation)

## 🔄 Functional Buttons

- `Add Record`: Create a new entry
- `Save Record`: Save changes to the current record
- `Delete Record`: Remove selected employee
- `Next/Back Record`: Navigate through records
- `Find`: Search employee by ID

## 👨‍💼 Sample Fields in Employee Table

- `EmpID`, `FirstName`, `LastName`, `Gender`
- `Birthdate`, `Mobile No`, `Email`, `Address`
- `Department`, `Job_Role`, `Rank`
- `Bank`, `Salary_periods`, `Base salary`, `Taxable_allowance`, `Non_taxable_allowance`

## 📷 Screenshots

### 1. Profile View (Form-based interface)
![Profile Form](https://github.com/user-attachments/assets/3aeec5bc-65a8-4152-b7dc-dee2d54e1c02)

### 2. DataSheet View (All Employee Records)
![DataSheet View](https://github.com/user-attachments/assets/b9c454fe-284c-40d2-ab60-34c69c2b4909)

### 3. Table Design View (Employee Table Fields)
![Table Structure](https://github.com/user-attachments/assets/ed7f8e8a-35fe-43fb-99fe-c978e73677db)

> 📂 Note: This project is intended for learning and prototyping purposes.

---

## 🤝 Contributing

Pull requests are welcome. For significant changes, please open an issue first to discuss what you'd like to change.

---

## 📧 Contact

Developed by **Om Raut**  
📩 Email: omsambhajiraut@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/omraut31) | [GitHub](https://github.com/omraut31)
