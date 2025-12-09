# Personalized Skincare Treatment Efficacy Dashboard (Tableau Project)

A comprehensive Data Analysis project that identifies the most effective skincare treatments for different patient skin types, driving personalized recommendations and improving customer satisfaction.

## 🎯 Project Overview & Goal

This project is a **comprehensive Data Analysis solution** created for a fictional skincare brand. The primary goal is to perform **diagnostic analysis** to identify which specific treatments are most effective based on individual patient characteristics, such as **Skin Type** and **Age Group**. The findings provide actionable insights for personalized marketing and product development.

This project serves as a strong demonstration of foundational Data Analyst skills for a beginner portfolio, including: multi-table joining, KPI definition, and interactive dashboard design.

---

## 🚀 Key Findings & Business Recommendations

The analysis was based on the **Improvement Score** (change in skin health score from baseline).

| Finding | Recommendation for Skincare Brand |
| :--- | :--- |
| **High Efficacy for Oily Skin:** Treatment **\#7** consistently outperformed competitors, showing a median Improvement Score **30% higher** than the overall average for patients with **Oily Skin**. | Prioritize marketing campaigns for Treatment \#7 specifically targeting the 'Oily Skin' customer segment. |
| **Aging Skin Group Performance:** The **50+** age group showed the lowest overall improvement rates across all treatments, indicating a potential product gap. | Invest in R&D for a new treatment targeting age-related skin concerns, or revise existing treatment protocols for this demographic. |
| **Data Integrity Note:** The analysis was run using an **Inner Join**, only including patients with completed treatment records. | **Future Recommendation:** Transition to a **Left Join** in the ETL process to include all enrolled patients and track non-participation rates as a critical business metric. |

---

## 💻 Tools & Technology Stack

* **Visualization & Dashboarding:** Tableau Desktop / Tableau Public
* **Data Source:** Multiple CSV Files (`patient`, `treatment`, `patient_treatment`)
* **Methodology:** Principles of SQL (relational joins) and Python/Pandas (data cleaning and calculation of new KPIs).

---

## 🔗 How to View the Dashboard

The completed dashboard can be viewed in two ways:

1.  **Live View (Recommended for Recruiters):**
    * **[PASTE YOUR TABLEAU PUBLIC LINK HERE]**
    * *(You must first publish your dashboard to Tableau Public and get the shareable link.)*

2.  **Download and Explore:**
    * Download the complete workbook file: `personalized-skincare-dashboard.twbx`
    * Open the file using **Tableau Desktop** or **Tableau Reader** to interact with the visualizations.

---

## 📂 Repository Contents

| File/Folder | Description |
| :--- | :--- |
| `README.md` | This project summary, findings, and tools used. |
| `personalized-skincare-dashboard.twbx` | The complete, packaged Tableau file, including all visualizations and embedded data. |
| `patient_data/` | Folder containing the raw source files (`.csv`) for data preparation. |
| `data_prep_script.py` | *(Optional: Your Python/R/SQL script used for initial data cleaning/joining.)* |

---

*Thank you for reviewing my work. Feel free to contact me with any questions.*
