# Educational-Organisation-Using-ServiceNow
Automates student admissions and academic tracking using ServiceNow workflows, tables, and client scripts.
🎓 Educational Organisation Management System (ServiceNow)

A real-time Educational Management System built on the ServiceNow platform to automate student admission and academic progress tracking.
The system replaces manual paperwork with a structured digital workflow using custom tables, forms, client scripts, and process flows.

It helps institutions maintain organized student records, monitor admission stages, and automatically calculate academic performance.

📌 Problem Statement

Educational institutions often manage admissions and student records manually.
This leads to:

Data duplication

Calculation mistakes

Difficulty tracking admission status

Time-consuming paperwork

This project digitizes the entire process using ServiceNow automation.

🚀 Solution

The application provides a centralized platform where administrators can:

Register students

Process admissions

Track admission lifecycle

Record subject marks

Automatically calculate totals & results

All actions are automated using ServiceNow scripting and workflows.

🧩 Modules Implemented
1️⃣ Student (Salesforce) Table

Stores primary student details.

Admin Number (Auto Generated)

Student Name

Grade

2️⃣ Admission Table

Extends the student table and manages admission lifecycle.

Admission Number

School & Location details

Purpose of join

Admission Status

3️⃣ Student Progress Table

Tracks academic performance.

Subject marks

Total (Auto calculated)

Percentage (Auto calculated)

Result (Auto updated)

⚙️ Automations Implemented

Auto generate admin numbers

Auto fetch student details from admission

Auto fill address based on pincode

Auto calculate total marks

Auto calculate percentage & result

Disable manual editing for calculated fields

🔄 Admission Workflow

New → In Progress → Joined → Rejoined → Rejected → Closed → Cancelled

The process flow visually tracks student admission stages in real time.

🛠️ Technologies Used

ServiceNow Platform

Tables & Relationships

Form Designer

Client Scripts (onChange, onLoad)

Process Flow

Number Maintenance

📊 Advantages

Reduces manual work

Improves accuracy

Easy status tracking

Centralized data storage

Scalable and customizable

⚠️ Limitations

Requires ServiceNow knowledge

Customization may take time

Enterprise usage requires license

🔮 Future Enhancements

Dashboard & reports

Teacher module

Mobile application

AI performance prediction

🎯 Learning Outcomes

Through this project, I learned:

ServiceNow application development

Table relationships & extending tables

Form customization

Workflow automation

Client-side scripting

Real-world business process implementation

👨‍💻 Author

Ram Ganesh Karri
B.Tech – Information Technology
