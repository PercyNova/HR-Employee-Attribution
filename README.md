# HR Employee Attrition Analysis

## Project Title:
**HR Employee Attrition Analysis**  
**Goal:** Predict and understand factors influencing employee turnover.

## Business Problem:
Employee attrition is a significant challenge for HR departments, as it leads to higher recruitment and training costs. The company aims to:
- Identify patterns and reasons behind employee turnover.
- Predict which employees are likely to leave.
- Provide actionable recommendations to reduce attrition.

## Objective:
The objective of this project is to analyze an HR dataset to determine the factors that contribute to employee attrition and create a predictive model to foresee future attrition. Through the analysis, insights will be provided to assist HR in improving retention strategies.

---

## Dataset:
This analysis uses a publicly available HR dataset that contains information about employees, their tenure, job satisfaction, compensation, and more. Key attributes include:
- **Age**, **Salary**, **Job Role**, **Department**, **Years at Company**
- **Attrition** (whether an employee left or stayed)

---

## Approach:

### 1. Data Exploration & Preprocessing:
- **Data Cleaning:** Removed missing values, handled categorical variables, and standardized formats.
- **Exploratory Data Analysis (EDA):** Visualized distributions and relationships to identify trends and patterns in the data.

### 2. Descriptive Analytics:
- Calculated the **overall attrition rate**.
- Analyzed **attrition by department** to identify high-risk groups.
- Investigated the impact of **age**, **salary**, and **years at company** on attrition.

### 3. Predictive Analytics (Optional):
- Built a **predictive model** (Logistic Regression or Decision Tree) to predict whether an employee would leave based on various factors.
- Evaluated model performance using accuracy and confusion matrix.

---

## Insights & Recommendations:
### Key Insights:
- High attrition rates were observed in certain departments, such as Sales.
- Employees with lower salaries were more likely to leave the company.
- Younger employees tended to leave earlier than older ones.

### Recommendations for HR:
- Improve **salary packages** and benefits for high-risk departments.
- **Focus on career development** programs to retain younger employees.
- **Implement work-life balance** initiatives for at-risk groups.

---

## Tools & Libraries:
- Python
- Pandas
- Matplotlib, Seaborn (for visualization)
- PowerBI

---

## Next Steps:
1. **Refine the predictive model** for better accuracy.
2. **Automate the model** for continuous attrition predictions.
3. **Develop an interactive dashboard** to allow HR to monitor attrition risk in real-time.

---
## Screenshot
![image](https://github.com/user-attachments/assets/2bef0c14-3f07-4b4b-a194-a3e175eb5848)


## How to Run This Project:
1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Run the Jupyter notebook for analysis (`attrition_analysis.ipynb`).

---

## Resources:
- [Kaggle HR Dataset Link](https://www.kaggle.com/datasets/tsmith007/hr-employee-attrition)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
