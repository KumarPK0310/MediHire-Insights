
# 🧠 MediHire Insights
**Revolutionizing Healthcare Workforce Decisions with Power BI**

---

## 📚 Table of Contents
- [Dashboard Modules Overview](#-dashboard-modules-overview)
- [Project Description](#-project-description)
- [Final Deliverables](#-final-deliverables-submission-files)
- [Validation Approach](#-validation-approach)
- [How to Use](#-how-to-use)
- [Team Contributions](#-team-contributions)
- [Project Structure](#-project-structure)
- [Acknowledgements](#-acknowledgements)

---

## 📊 Dashboard Modules Overview
Our Power BI solution is structured into five purpose-driven modules that address strategic healthcare HR needs:

### 🩺 1. Executive Overview
🔍 **Purpose:** Provide a bird’s-eye view of organization-wide workforce statistics.  
📌 **Key Insights:**
- Total Employees, Avg. Salary, Avg. Experience, and Job Satisfaction.
- Department-wise income breakdown.
- Gender composition and top job roles by volume.

<img width="1269" alt="Screenshot 2025-05-05 at 9 12 51 PM" src="https://github.com/user-attachments/assets/80309606-ce92-4df9-a8cb-5fc90185a9c0" />


### 🧑‍⚕️ 2. Skill Demand Dashboard
📈 **Purpose:** Analyze skills required across roles and departments to guide training and hiring.  
📌 **Key Insights:**
- Skills mapped per role.
- High-frequency skills by department.
- Unpivoted, cleaned `RequiredSkills` field.

<img width="1269" alt="Screenshot 2025-05-05 at 9 13 20 PM" src="https://github.com/user-attachments/assets/933c1ce5-a2c9-4d39-8133-2fd4ecf56d78" />


### 💵 3. Salary Insight Dashboard
💰 **Purpose:** Reveal compensation trends across job roles, experience, and visa status.  
📌 **Key Insights:**
- Avg. Monthly Income by Job Role and Visa Type.
- Min/Max salary boundaries.
- Salary hike correlation with tenure.

<img width="1269" alt="Screenshot 2025-05-05 at 9 13 36 PM" src="https://github.com/user-attachments/assets/819b8b55-964b-4d94-99a4-37d2702de6d5" />


### 🛂 4. Visa Insights Dashboard
🌍 **Purpose:** Evaluate employment dynamics by visa status — H1B, OPT, STEM OPT, Green Card, US Citizens.  
📌 **Key Insights:**
- Distribution of employees by visa category.
- Salary hike percentages across visa types.
- Visa demographics per department and job role.

<img width="1269" alt="Screenshot 2025-05-05 at 9 13 49 PM" src="https://github.com/user-attachments/assets/96206c0e-6581-4956-a97b-460af98b8553" />


### ⚙️ 5. Settings Page
🛠️ **Purpose:** Enable slicing across all dashboards using filters like Marital Status, Education Field, Shift, and Visa Type.  
📌 Fully interactive slicers to dynamically adjust all modules.

<img width="1269" alt="Screenshot 2025-05-05 at 9 14 04 PM" src="https://github.com/user-attachments/assets/9b524103-34f8-4615-b57e-2119ac6393ed" />

---

## 💡 Project Description
**MediHire Insights** is a Power BI-powered workforce analytics application crafted to support HR managers and healthcare executives in improving:  
- Talent planning and retention  
- DEI (Diversity, Equity, Inclusion) tracking  
- Skills development strategies  
- Visa and international workforce visibility  
- Salary equity assessments  

It integrates structured insights from over 3,500 anonymized employee records derived from the [Kaggle classification-models-logistic dataset](https://www.kaggle.com/code/ilarrumbide/classification-models-logistic/data), reshaped for healthcare use.

---

## 📂 Final Deliverables (Submission Files)

| File | Description |
|------|-------------|
| `watson healthcare.pbix ` | Final Power BI application |
| `watson_healthcare_updated_skills.csv` | Transformed dataset with clean job roles, skills, and salary fields |
| `Formulas_And_PythonScript.docx` | M-code exported from Power Query steps |
| `README.md` | Overview and instructions (this file) |

---

## 🧪 Validation Approach
- Power Query used for skill parsing and job title normalization  
- Schema validated in Power BI model view (1:M relationships)  
- Outliers filtered, missing values addressed, and business logic added via DAX  
- Visuals were validated through mock scenarios and peer feedback  

![image](https://github.com/user-attachments/assets/ed8e63f8-73ca-45e5-8a82-f5a517588116)

---

## 🧭 How to Use
- Open `watson healthcare.pbix` in Power BI Desktop  
- Explore dashboards via tabs or bookmarks  
- Use slicers to segment by department, visa, role, etc.  
- Hover for tooltips; export any visual as a report  

---

## 🤝 Team Contributions

| Team Member       | Contributions                                                |
|-------------------|--------------------------------------------------------------|
| **Prasanna**      | Project lead, charter definition, traceability matrix       |
| **Bhanuprakash**  | Data transformation, Power Query steps, skill parsing       |
| **Rajashekar**    | UI/UX design for Power BI dashboard                         |
| **Vinay**         | DAX development, salary calculations, logic validation      |
| **Poojitha**      | Documentation, visual feedback, matrix documentation        |
| **Sai Srujana**   | Quality assurance, testing, final application verification  |

---

## 🗃️ Project Structure

```
medihire-insights/
├── watson healthcare.pbix           # Final Power BI Dashboard
├── watson_healthcare_updated_skills.csv              # Cleaned and transformed dataset
├── Formulas_And_PythonScript.docx            # Power Query M code
├── README.md                        # This documentation file
```

---

## 🙌 Acknowledgements
- **Tools Used:** Power BI, Excel, Power Query, DAX  
- **Institution:** Saint Louis University — MS in Health Informatics Program  
- **Mentorship:** Special thanks to our professors and industry reviewers

---

🔬 *MediHire Insights™ — Turning Healthcare HR Data Into Smart Strategy.*
