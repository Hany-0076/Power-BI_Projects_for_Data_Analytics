# Power BI Projects for Data Analytics
A collection of Power BI projects focused on data analytics, including:

- 📊 **Interactive Visuals & Charts**  
- 🎨 **Creative Dashboard Design**  
- ♻️ **Power Query for ETL (Extract, Transform, and Load)**  
- 🗂️ **Data Modeling & Star Schema Design**  
- 🖇️ **Relationship Management**  
- 🧠 **DAX Measures & Calculations**  
- 🧮 **Calculated Columns & Tables**  
- 🎚️ **Slicers, Filters & Dynamic Parameters**  
- 📌 **Bookmarks & Page Navigation**  
- 🎯 **KPI Tracking**

</br>

## 1) 🚀 Data Careers Overview
This Power BI project provides an interactive look into careers in the Data industry. It includes two connected dashboards: a main overview dashboard and a drill-through details dashboard. The project highlights job demand, required skills and its popularity, salary ranges, and global hiring trends for roles such as Data Analyst, Data Engineer, and Data Scientist. Users can explore how each role compares in terms of skills, salaries, and job availability across different countries.

### 🟡 Overview Dashboard
The main dashboard gives a broad overview of the data job market. It displays total job count, average skills per job, median salaries, and the most in-demand technical skills. Users can filter results by job title and country to see how job demand and salaries change based on their selections. This dashboard is designed to help users quickly understand overall trends in the Data field.
<p align="center">
<img width="1000" height="500" alt="Data Careers Overview" src="https://github.com/user-attachments/assets/6a52fe03-1d01-4d42-992c-6ba310f58292" />
</p>

### 🟡 Drill-Through Specific Roles Dashboard
The drill-through dashboard provides a deeper, role-specific breakdown based on the selected job title from the main report. It highlights important job attributes such as remote-work availability, degree requirements, health insurance coverage, hiring platforms, and global job distribution. This page gives a focused view that helps users understand the characteristics, benefits, and hiring patterns associated with each individual Data role.
<p align="center">
<img width="1742" height="978" alt="Job Title Detials" src="https://github.com/user-attachments/assets/bd515ba3-eb05-409e-b7e0-963f5d65573f" />
</p>

### 🟡 Data Model Overview
This project is built on a structured Data Model that follows a **star schema design**. The model includes one central Fact Table containing the main metrics such as job title, salaries, and job countries the fact table connected to several Dimension Tables that store descriptive information like job skills, skills types, and companies information.

This structure improves performance, ensures clean relationships, and makes analysis easier by allowing the dashboard visuals to filter and interact smoothly. The model also supports flexible drill-down, filtering, and detailed exploration across different data categories.
<p align="center">
<img width="1600" height="702" alt="Data Careers Overview Model" src="https://github.com/user-attachments/assets/8c929f23-cedd-4f3c-8583-8c6970a2da5b" />
</p>

### 🟡 DAX Calculations Overview
This project uses a set of core DAX measures that provide the main calculations for the dashboard. These measures include Job Count, Skill Count, Median Yearly Salary, and Skill Per Job, each designed to transform raw data into meaningful insights that respond to user filters and selections.

This set of measures strengthens the analysis by ensuring accurate calculations, dynamic updates, and consistent results across visuals. They help the dashboard reflect real-time interactions, support comparisons between job roles and countries, and enable deeper exploration of patterns in skills, salaries, and job demand.
<p align="center">
<img width="406" height="436" alt="Data Careers Overview DAX and Measures" src="https://github.com/user-attachments/assets/3e53bf00-e70d-4e1e-9c85-cebb9dc6664e" />
</p>




