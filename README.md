# 🏥 Bati General Hospital - Automated Data Entry Form (Excel)

This project is an **automated patient data entry system** designed in **Microsoft Excel** using **VBA Macros**. It streamlines the registration process for patients at **Bati General Hospital**, reducing manual workload and improving accuracy.

## 📋 Form Overview

The data entry form collects and organizes patient information through a user-friendly Excel interface. Key functionalities include **dropdown selections**, **macro-enabled automation**, and a **submit button** that safely stores entries in a structured database sheet.

### ✅ Fields Included in the Form

| Field Name           | Type               |
|----------------------|--------------------|
| Name                 | Text Input         |
| Sex                  | Dropdown (Male/Female/Other) |
| City                 | Text Input         |
| Region               | Dropdown (Regions in Ethiopia) |
| Age                  | Numeric Input      |
| Phone Number         | Numeric Input      |
| Card Number          | Manual Input |
| Preferred Department | Dropdown (e.g., OPD, Pediatrics, Lab, etc.) |
| Date                 | Auto-filled (current date) |
| Submit Button        | Macro-enabled for saving data |

> 🔁 **Dropdowns** ensure data consistency and fast entry.
> 🖱️ **Submit Button** uses VBA to append data to the next available row.

---

## ⚙️ Features

- 🧠 **Macro Automation**: Adds each patient’s data into a log sheet upon clicking "Submit".
- ✅ **Data Validation**: Ensures correct formatting and reduces entry errors.
- 🧾 **Well-Structured Database Sheet**: Patient information is stored row-wise with headers.
- 📆 **Date Auto-fill**: Captures current date (the date on the computer) during entry automatically.
- 🔒  **Database Sheet-Protected**: The Database sheet is protected from any formatting. Only permitted person who knows the protect password can manipulate it.

---

## 🛠️ Technologies Used

- Microsoft Excel (.xlsm)
- VBA (Visual Basic for Applications)
- Data Validation Lists

---

## 📁 File Structure
📂 Bati-General Hospital Form: [This is the main project folder](https://github.com/Molla-Adugna/Automated-Data-Entry-Form/blob/main/Bati_General_Hospital_Form.xlsm)   
📄 Patient_Entry_Form (Screenshoot):[This is screenshoot of the Data Entry Form (with Macros enabled)](https://github.com/Molla-Adugna/Automated-Data-Entry-Form/blob/main/Screenshot%20(364).png)  
📄 All_Patients_Detail_information (Screenshoot):  [This is All patients information sheet](https://github.com/Molla-Adugna/Automated-Data-Entry-Form/blob/main/Screenshot%20(366).png)  
📑 README.md: [This is the README.md](https://github.com/Molla-Adugna/Automated-Data-Entry-Form)       


---
## ▶️ How to Use  
1. Open the Patient_Entry_Form.xlsm file in Microsoft Excel.  
2. Make sure to enable macros when prompted.  
3. Fill in the patient details using the form interface.  
4. Click the Submit button to save the entry.  
5. Data will bappended to the database sheet automatically.

---

## 🔐 Security Note 

⚠️Ensure macros are only enabled if you trust the source of the file. This file is safe and developed for internal use at Bati General Hospital.  
⚠️The patient Names and all informations about it are NOT reall, rather I used it just for an example purpose.

---

## 📞 Contact
For updates, support, or customization:

Developed by: Molla Adugna  

📧 Email: mollaadugna@gmail.com  

## 📍 Location: Dessie, Ethiopia


## 📸 Screenshots
1. The **form** that allows the receptionist to enter data about patients.![alt text](<Screenshot (364).png>)

---

2. An **Excel sheet** where all the information that the receptionist fills in on the form will be stored.![alt text](<Screenshot (366).png>)
