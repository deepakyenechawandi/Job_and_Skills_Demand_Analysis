# 📊 Job & Skills Demand Analysis (Naukri EDA)

This project performs an Exploratory Data Analysis (EDA) on job listings from the Naukri dataset to uncover insights about hiring trends, in-demand skills, job roles, and experience/salary distributions in the Indian job market.

---

## 🔍 Project Objectives

- Analyze job demand by location, company, and job title  
- Identify top technical and soft skills required in job descriptions  
- Examine experience and salary patterns across roles  
- Visualize trends using informative charts

---

## 🛠️ Tools & Technologies

- **Python** (pandas, matplotlib, seaborn)
- **Jupyter Notebook**
- **Excel** (for initial inspection, optional)
- **Data Source**: Naukri job listing snapshot (CSV or Excel)

---

## 📂 Dataset Overview

The dataset includes the following fields:

- `company`, `education`, `experience`, `industry`, `jobdescription`  
- `joblocation_address`, `jobtitle`, `payrate`, `numberofpositions`  

---

## 📈 Key Insights & Outputs

### 🔝 Top 10 Job Locations
![Top Locations](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/top_locations.png)

### 🏢 Top Hiring Companies
![Top Companies](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/top_companies.png)

### 🧑‍💼 Common Job Titles
![Top Titles](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/top_titles.png)

### 🛠️ In-Demand Skills
![Top Skills](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/top_skills.png)

### 📊 Experience & Salary Distribution
![Experience](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/experience_distribution.png)  
![Salary](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/salary_distribution.png)

### 📉 Experience vs Salary Correlation
![Exp vs Salary](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/experience_vs_salary.png)

### 🔥 Heatmap of Numeric Correlations
![Correlation Heatmap](https://github.com/deepakyenechawandi/Job_and_Skills_Demand_Analysis/blob/main/Output/correlation_heatmap.png)

---

## 🚀 How to Run

1. Clone the repository or download the project folder  
2. Install dependencies  
   ```bash
   pip install pandas matplotlib seaborn openpyxl
