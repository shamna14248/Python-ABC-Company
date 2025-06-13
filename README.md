
# ABC Company Employee Data Analysis

## 📌 Project Overview

This project analyzes employee data from **ABC Company** (458 rows × 9 columns) to provide insights on team distribution, position segregation, salary expenditure, age trends, and correlations. The objective is to help the company understand its workforce better using **Python** for data analysis and visualization.

---

## 📂 Dataset

* **Source:** [ABC Company Dataset](https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link)
* **Rows:** 458
* **Columns:** 9
* **Features include:**

  * `Age`
  * `Salary`
  * `Height`
  * `Team`
  * `Position`
  * *(and other attributes)*

---

## ⚙️ Preprocessing

* Replaced the `Height` column with random values between 150 and 180.
* Ensured data consistency and integrity before performing analysis.

---

## 📊 Analysis Tasks

* **Team-wise Distribution:** Calculated the number of employees in each team and the percentage distribution across all teams.
* **Position-wise Segregation:** Counted employees in each position.
* **Predominant Age Group:** Grouped employees into age ranges (`<25`, `25-30`, `30-35`, `35-40`, `40+`) and identified the most common group.
* **Highest Salary Expenditure:** Identified the team and position with the highest total salary expenditure.
* **Correlation Between Age and Salary:** Analyzed and visualized the correlation between employee age and salary.

---

## 📈 Visualizations

The following charts were created to present findings clearly:

* Bar chart for team-wise employee count
* Pie chart for team-wise percentage split
* Bar chart for position-wise count
* Bar chart for age group distribution
* Scatter plot showing age vs salary correlation

---

## 📖 Insights

* Identified the team and position with the largest share of employees.
* Highlighted the most common age group within the workforce.
* Found the team and position contributing most to total salary expenditure.
* Determined the nature of correlation between age and salary (positive, negative, or weak/strong relationship).

---


## 🛠️ Requirements

```bash
pip install pandas matplotlib seaborn numpy
```

---


## 💡 Notes

* This project could be extended with additional visualizations (e.g., salary distribution by team or position).

