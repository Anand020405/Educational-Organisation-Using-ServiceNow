# 🎓 Educational Organisation Using ServiceNow  

> **A complete workflow automation project for educational administration using ServiceNow**

---

## 📘 Project Overview  

The **Educational Organisation Using ServiceNow** project is a comprehensive platform designed to automate administrative and academic operations in educational institutions.  

It simplifies **student admissions**, **academic record management**, and **performance tracking** by leveraging the **ServiceNow** platform’s capabilities such as **custom tables**, **process flows**, and **client scripts**.  

This project demonstrates how low-code automation can improve institutional efficiency, reduce manual errors, and provide transparent, data-driven operations.  

---

## 🧩 Key Features  

- 🧾 **Automated Admissions:** Streamlined student admission workflow with dynamic form filling.  
- 📊 **Performance Tracking:** Auto-calculation of total, percentage, and result for each student.  
- 🔁 **Process Flow Management:** Tracks admission status (New → Joined → Closed).  
- ⚙️ **Client Script Automation:** Populates fields and computes grades in real-time.  
- 🔐 **Secure and Scalable:** Role-based access and centralized data management within ServiceNow.  

---

## 🏗️ System Architecture  

```text
+-------------------------------------------------------------+
|                       ServiceNow UI                         |
| (Admission Form, Progress Dashboard, Status Visualization)  |
+---------------------------↑---------------------------------+
                            |
                            | User Input / Form Data
                            ↓
+-------------------------------------------------------------+
|                   Business Logic Layer                      |
| - Client Scripts (Auto Populate, Total, Result)             |
| - Process Flows (Admission Lifecycle)                       |
+---------------------------↓---------------------------------+
                            |
                            | Data Operations
                            ↓
+-------------------------------------------------------------+
|                     Database Layer (Tables)                 |
| - Salesforce Table: Student Master Data                     |
| - Admission Table: Enrollment Details                       |
| - Student Progress Table: Marks & Results                   |
+-------------------------------------------------------------+
📊 Workflow Summary
1️⃣ Student Data Creation: Admin adds base details in Salesforce Table.
2️⃣ Admission Process: Admission Table records and tracks each application.
3️⃣ Academic Progress: Marks entered in Student Progress Table trigger automated total and result calculation.
4️⃣ Process Flow: Transitions admission through defined stages.
5️⃣ Monitoring: Administrators view overall progress and performance dashboards.

⚙️ Tools & Technologies
Component	Technology Used
Platform	ServiceNow Developer Instance
Scripting Language	JavaScript
Automation	Client Scripts, Process Flow Designer
Performance Testing	Apache JMeter
API Testing	Postman
IDE	Visual Studio Code
Reporting	ServiceNow Dashboard / Excel
Version Control	GitHub

📁 Repository Structure
Educational-Organisation-Using-ServiceNow/
│
├── 📄 1_Ideation_Phase_Report.md
├── 📄 2_Performance_Testing_Phase_Report.md
├── 📄 3_Project_Design_Phase_Report.md
├── 📄 4_Project_Planning_Phase_Report.md
├── 📄 5_Requirement_Analysis_Phase_Report.md
│
└── 📄 README.md
🧠 Project Phases
Phase	          Document	       Description
1️⃣ Ideation Phase	View File	Defines concept, objectives, and feasibility.
2️⃣ Performance Testing	View File	Evaluates system responsiveness and scalability.
3️⃣ Design Phase	View File	Outlines architecture, data flow, and module design.
4️⃣ Planning Phase	View File	Establishes schedule, milestones, and resource plan.
5️⃣ Requirement Analysis	View File	Defines functional and non-functional requirements.

📈 Expected Outcomes
Centralized and automated educational data management.

Reduction in manual work and improved accuracy.

Transparent admission and result tracking workflows.

Scalable and maintainable ServiceNow application.

🧩 Future Enhancements
📱 Integration with mobile and student portals.

🤖 AI-based performance prediction for students.

🧾 Auto-generated progress reports and result sheets.

📡 API integration with Learning Management Systems (LMS).


📬 Contact
📧 Email: bvanandbv@gmail.com
🌐 GitHub Repository: https://github.com/Anand020405/Educational-Organisation-Using-ServiceNow
🏫 Institution: Amrita College of Engineering and Technology

