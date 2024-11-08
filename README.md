# Data Science Job Salaries Analysis Dashboard

An interactive Tableau dashboard that visualizes key insights into data science job salaries, leveraging data points like experience level, job type, company size, and geographic distribution. This dashboard serves as an exploration tool for understanding trends and patterns in compensation across the global data science industry.

## [🔗 Dashboard Preview](https://public.tableau.com/app/profile/vishnu.vamshi.vidyapathi.sharma/viz/DataScienceJobsSalary_17310380504220/Dashboard1) 

---

## 📊 Project Overview

The **Data Science Job Salaries Analysis Dashboard** is built to provide recruiters, job seekers, and industry analysts with insights into how data science roles are compensated based on experience, location, and other critical job attributes. It combines various visualization techniques to allow deep dives into salary distributions, top regions for data science employment, and preferred experience and job types.

### Key Highlights
- **Analyze** company demographics by size and location.
- **Explore** salary ranges by experience level and job type.
- **Identify** top countries where data science roles are most prevalent.
- **Compare** average salaries across job roles and regions.

---

## 📂 Dataset Details

This project utilizes a dataset from Kaggle, containing real-world data on data science job salaries.

- **Dataset Source**: [Kaggle - DS Salaries Dataset](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)
- **File Used**: `ds_salaries.csv`

### Main Attributes:
- **ID**: Unique identifier for each role
- **Work Year**: Year of the salary data
- **Experience Level**: Levels include **Entry (EN)**, **Intermediate (MI)**, **Senior (SE)**, and **Expert (EX)**
- **Employment Type**: Types include **Full-Time (FT)**, **Part-Time (PT)**, **Contract (CT)**, and **Freelance (FL)**
- **Job Title**: Specific title of the data role
- **Salary**:	The total gross salary amount paid
- **Salary Currency**:	The currency of the salary paid as an ISO 4217 currency code
- **Salary in USD**: Annual salary, normalized to USD
- **Employee Residence**: Employee's residing country
- **Remote Ratio**: The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)
- **Company Location**: The country of the employer's main office or contracting branch as an ISO 3166 country code
- **Company Size**: Categorical representation of company size: **Large (L)**, **Medium (M)**, **Small (S)**

---

## ⚙️ Project Setup

### Prerequisites
- **Tableau**: Tableau Desktop or Tableau Public (required to open or modify the dashboard).
- **Dataset**: [Download the dataset](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)

### Steps to Recreate the Dashboard
1. **Data Preparation**:
   - Import `ds_salaries.csv` into Tableau.
   - Assign aliases to categorical values (e.g., **EN** -> **Entry**, **MI** -> **Intermediate**).
2. **Visualizations**:
   - Create charts as described in the **Dashboard Components** section.
   - Use calculated fields to convert salaries to standardized ranges if needed.
3. **Formatting**:
   - Customize color schemes, fonts, and layouts to improve readability and aesthetics.
4. **Filters and Interactivity**:
   - Add dynamic filters for **Country**, **Job Title**, and **Company Size** to allow detailed data exploration.

---

## 🔍 Insights & Observations

### Key Insights
- **Experience Matters**: Higher experience levels command significantly higher average salaries across most locations.
- **Geographical Trends**: Certain regions, especially in North America and Western Europe, dominate in terms of data science salaries and job prevalence.
- **Remote Work Prevalence**: The data suggests that remote roles are increasingly popular in the data science field, with a sizable proportion of jobs offering remote flexibility.

### Questions Answered
1. **Which countries offer the highest average salaries for data scientists?**
2. **What’s the salary gap between entry-level and senior-level data science roles?**
3. **How does employment type affect salary distribution?**

---

## 🚀 Future Enhancements

- **Trend Analysis**: Incorporate year-over-year changes in salaries and remote work ratios.
- **Job Role Breakdown**: Add more detailed visualizations based on specific data science roles (e.g., Data Engineer, ML Engineer).
- **Regional Cost of Living Adjustment**: Adjust salaries based on regional living costs to reflect real earnings.

---

## 🛠️ Tools & Technologies Used

- **Tableau Desktop/Public**: For building and visualizing the dashboard.

---

## 🎓 Acknowledgments

Special thanks to [Kaggle](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries) for the dataset and the **Tableau Community** for inspiration and resources that assisted in building this dashboard.


