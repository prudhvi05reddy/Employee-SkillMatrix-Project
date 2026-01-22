# 📊 Employee Skill Matrix & Training Tracker  

## 📌 Overview  
The Employee Skill Matrix & Training Tracker is an HR automation project designed to manage employee skill data, identify skill gaps, and automate training and review reminders. The project uses SharePoint as a centralized data source and Power Automate to trigger workflows that reduce manual HR effort and improve workforce skill monitoring.

---

## 🎯 Project Goals  
- Centralize employee skill and training data  
- Identify low skill levels and skill gaps  
- Automate training reminder notifications  
- Schedule periodic employee skill reviews  
- Improve workforce development and upskilling  

---

## 🛠 Technology Stack  
- **SharePoint (Microsoft Lists)** – Data storage and management  
- **Power Automate** – Workflow automation and email notifications  
- **Excel** – Dataset preparation and structured data handling  

---

## 🗂 Data Management (SharePoint)  
Employee information is maintained in a SharePoint Microsoft List which acts as the main data source for the automation workflows.

### Stored Information Includes:  
- Employee and department details  
- Skill names and proficiency levels  
- Training completion status  
- Certifications and feedback  
- Review tracking information  

This centralized structure ensures consistent data access across all workflows.

---

## 🔁 Automated Workflows (Power Automate)

### ✅ Flow 1: Low Skill Reminder Training  

**Purpose:**  
Automatically notify employees when their skill level falls below the defined threshold.

**Process:**  
- Runs on a scheduled basis  
- Fetches employee data from SharePoint  
- Checks skill levels  
- Identifies low-skill employees  
- Sends training reminder emails  

**Business Value:**  
- Encourages continuous learning  
- Reduces manual follow-ups  
- Improves skill development  

---

### ✅ Flow 2: Scheduled Review (Every 90 Days)  

**Purpose:**  
Ensure periodic employee skill evaluations.

**Process:**  
- Runs every 90 days  
- Checks last review date  
- Identifies employees due for review  
- Sends automated review reminder emails  

**Business Value:**  
- Maintains structured performance reviews  
- Supports long-term workforce improvement  

---

## 🏗 System Architecture  
1. Employee data is stored in SharePoint Lists  
2. Power Automate workflows run on scheduled triggers  
3. Business conditions evaluate skill levels and review timelines  
4. Automated email notifications are generated based on logic  

This architecture enables a fully automated and scalable HR skill management system.

---

## ✅ Conclusion  

The Employee Skill Matrix & Training Tracker demonstrates the effective use of SharePoint and Power Automate to build a real-world HR automation solution. By centralizing employee skill data and automating training and review notifications, this project reduces manual workload and improves workforce development processes. It highlights practical low-code automation skills and showcases how modern tools can be used to support data-driven decision-making in organizational environments.

---

⭐ If you find this project useful, feel free to star the repository!
