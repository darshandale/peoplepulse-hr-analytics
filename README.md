# 📊 PeoplePulse: HR Analytics & Workforce Attrition Dashboard

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)

## 📌 Project Overview
**PeoplePulse** is an interactive, web-based HR analytics dashboard designed to diagnose workforce health and uncover the root causes of employee attrition. Built as a single-page application, it transforms a static HR dataset of 5,000 employees into a dynamic, 5-tab analytical tool that empowers HR leaders to make data-backed retention decisions.

## 🎯 Business Problem
The organization is experiencing an **11.3% attrition rate**, leading to increased recruitment costs and loss of institutional knowledge. HR lacks a clear, unified view of *why* employees are leaving and *who* is most at risk. 

This dashboard solves that by:
1. Identifying the primary drivers of employee churn.
2. Segmenting employees by risk level to flag urgent retention cases.
3. Providing actionable, data-backed recommendations directly within the UI.

## 🖥️ Dashboard Features
The dashboard is divided into five analytical views, accessible via a custom navigation bar:

*   **1. Overview:** High-level KPIs (Total Employees, Attrition Rate, Avg Salary, High-Risk Count) alongside macro views of attrition by Department, Tenure, and Overtime. Includes a "Critical Finding" alert banner.
*   **2. Attrition Drivers:** Deep dives into Satisfaction, Engagement Scores, Stress Levels, Manager Relationships, and Age Groups. Includes an "Actionable Recommendations" card.
*   **3. Compensation:** Analyzes the impact of pay equity, Salary Bands, Job Levels, Gender, and Work Mode (Remote/Hybrid/On-site) on attrition. Includes a Department Snapshot table.
*   **4. Performance & Growth:** Explores the link between Performance Category, Promotion history, Promo Gaps, and Training Hours.
*   **5. Exit Analysis:** Visualizes the top reasons for voluntary vs. involuntary exits, alongside a geographic breakdown of attrition by Location.

## 💡 Key Insights Discovered
*   **The 9x Risk Gap:** The model flagged **75 high-risk employees** who churn at **58.7%**, compared to just **6.4%** for low-risk employees.
*   **New Hire Vulnerability:** Employees with less than 1 year of tenure exit at a staggering **29.1%** (the single largest leak).
*   **Burnout Factor:** Employees working overtime churn at **18.9%**, which is **2.4x higher** than those who do not (7.9%).
*   **Stalled Growth:** Employees who haven't received a promotion in 4+ years correlate with a **13.5% attrition rate**.
*   **Pay Equity Signal:** Employees who left earned **0.97x** their department average, compared to **1.0x** for those who stayed—indicating below-market pay is a measurable churn risk.

## 🛠️ Tech Stack & Architecture
*   **Frontend:** HTML5, CSS3 (Custom properties, Flexbox/Grid, Dark Mode support)
*   **Data Visualization:** Chart.js (Bar, Doughnut, and mixed Bar/Line charts)
*   **Data Logic:** Vanilla JavaScript (Dynamic DOM manipulation, tab routing, data binding)
*   **Data Source:** Pre-processed HR dataset (embedded as a JSON object in the script for zero-dependency deployment)

## 🚀 How to Run Locally
Because this is a zero-dependency, single-file project, getting it running is incredibly simple:

1. Clone the repository:
   ```bash
   git clone https://github.com/darshandale/PeoplePulse.git
