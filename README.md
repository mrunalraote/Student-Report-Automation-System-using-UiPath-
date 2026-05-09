# 📊 Student Report Automation System using UiPath

## 📌 Introduction
This project focuses on automating the process of generating and sending student academic reports via email using UiPath. The system reads student data from an Excel sheet, processes marks and attendance, and sends personalized performance reports to each student through SMTP email.

---

## 🎯 Objective
- Automate student report generation  
- Reduce manual emailing work  
- Ensure fast and error-free communication of academic performance  
- Improve efficiency using RPA (Robotic Process Automation)  

---

## 🛠️ Tools & Technologies Used
- UiPath Studio  
- Microsoft Excel  
- SMTP Email (Gmail)  
- VB.NET expressions (inside UiPath)  

---

## 📂 Input Data (Excel Structure)
The Excel sheet contains the following columns:

- Name  
- Email  
- Maths  
- Science  
- English  
- Attendance  
- Total  

Each row represents a student's academic record.

---

## 🔄 Workflow Description

### Step 1: Read Excel Data
- Excel file is read using **Read Range** activity  
- Data is stored in a DataTable (`dt`)  

### Step 2: Loop Through Each Student
- A **For Each Row** loop is used  
- Each student record is processed individually  

### Step 3: Generate Report Content
- Extract student details and marks  
- Display or calculate total marks  

### Step 4: Send Email via SMTP
- Configure Gmail SMTP  
- Send personalized email to each student using their email ID  

---

## 📧 Email Format Example
Each student receives an email containing:

- Greeting with student name  
- Subject-wise marks  
- Attendance details  
- Total marks  
- Closing message  

---

## 📤 Output
- Each student receives an individual email report  
- Data is automatically fetched from Excel  
- No manual intervention required  

---

## ✅ Advantages
- Saves time and effort  
- Reduces human errors  
- Fast communication of results  
- Scalable for large number of students  
- Easy to maintain and modify  

---

## 🧾 Conclusion
The Student Report Automation System demonstrates how UiPath can automate repetitive academic tasks efficiently. By reading data from Excel and sending personalized reports via email, the system improves productivity and accuracy. This project highlights the practical application of RPA in the education sector.

---

## 🚀 Future Enhancements
- Add grade calculation (A/B/C/D)  
- Generate PDF report cards  
- Create performance dashboard  
- Integrate database instead of Excel  
- Add email attachments  

---

## 👨‍💻 Author MRUNAL AROTE
Developed as a mini project for learning RPA and automation using UiPath.
