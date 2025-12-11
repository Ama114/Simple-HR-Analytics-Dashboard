# Simple-HR-Analytics-Dashboard

# 📊 HR Analytics Dashboard: Employee Attrition Analysis

## 1. Project Overview
* **Goal:** To analyze why employees are leaving the company (Attrition) and identify patterns to improve retention.
* **Dataset:** IBM HR Analytics Employee Attrition Data.
* **Total Records:** 1,470 Employees.
* **Tools Used:** Microsoft Excel (2016/2019/365).

---

## 2. Tools & Techniques Used
I used the following Excel features to build this project:
* **Data Cleaning:** Removing duplicates and checking for missing values.
* **Excel Tables:** Converted raw data into tables (`Ctrl + T`) for dynamic range.
* **Pivot Tables:** Used for data summarization and analysis.
* **Pivot Charts:** Visualized the data using Bar Charts and Column Charts.
* **Slicers:** Added interactivity to filter by 'Gender' and 'Education'.

---

## 3. Step-by-Step Process

### Step 1: Data Preparation
* Downloaded the raw dataset (CSV file).
* Checked for any blank rows or errors.
* Formatted the **"Monthly Income"** column to Currency ($) format.
* Created a "Status" column to clearly identify Active vs. Resigned employees.

### Step 2: Data Analysis (Key Questions)
I created three main Pivot Tables to answer these questions:
1.  **Attrition by Department:** Which department has the most resignations?
2.  **Income Analysis:** Do employees with low salaries leave more often?
3.  **Job Satisfaction:** How does satisfaction score (1-4) affect retention?

### Step 3: Dashboard Creation
* Designed a clean layout.
* Inserted **Clustered Column Charts** for Department analysis.
* Inserted **Bar Charts** for Income analysis.
* Added **Interactive Slicers** (Buttons) to filter the dashboard by:
    * Gender (Male/Female)
    * Education Field (Medical, Technical, Marketing, etc.)

---

## 4. Key Findings (Insights)

### 🚩 Insight 1: Salary Matters
* There is a significant gap in salary between those who left and those who stayed.
    * **Average Salary of Leavers:** ~$4,787
    * **Average Salary of Retained:** ~$6,832
* *Conclusion:* Lower income is a major driver for attrition.

### 🚩 Insight 2: High Attrition in R&D
* The **Research & Development (R&D)** department showed the highest number of resignations compared to Sales and HR.

### 🚩 Insight 3: Job Satisfaction
* Employees with a **Job Satisfaction score of 1 (Low)** had a higher tendency to leave the company within the first 2 years.

---

## 5. Strategic Recommendations
Based on the data, I recommend the following actions to the HR Management:

* **1. Review Compensation:** Conduct a salary review for employees earning below $5,000, especially in the R&D department.
* **2. Improve Onboarding:** Since many employees leave early, improve the training program for new joiners.
* **3. Focus on Employee Engagement:** Conduct meetings with employees who have low satisfaction scores to resolve their issues.

---

## 6. Future Improvements
To take this project to the next level, I plan to:
* Import this dataset into **Power BI** for more advanced visuals.
* Use **Python (Pandas)** to build a prediction model.
* Analyze "Work-Life Balance" and "Distance From Home" factors.

---

### 👤 Author
* **Name:** [Your Name Here]
* **Contact:** [Your Email or LinkedIn]
## Dashboards

<img width="1296" height="599" alt="image" src="https://github.com/user-attachments/assets/5c7614c0-bc3e-4edd-aa8d-b57d63f49abf" />
<img width="1282" height="613" alt="image" src="https://github.com/user-attachments/assets/40396b17-4aaf-47cb-b0c5-b166fee97a4a" />
<img width="1145" height="614" alt="image" src="https://github.com/user-attachments/assets/f12ff460-1245-469e-b8ca-84a196d61be2" />



