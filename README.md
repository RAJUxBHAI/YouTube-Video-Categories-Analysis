# Employee Burnout & Turnover Prediction Analysis

*(Self-Study Project for DBMS – ETB Subject)*

---

## Group Details

**Group 15 — Member Details**

* 341066 – Ramanjan Dutta
* 341090 – Nandini Singh
* 341077 – Mohammed Sarshad

*(Section B, PGDM-34)*

---

## Project Overview

This project focuses on analyzing **employee burnout and turnover patterns** using a large-scale workforce dataset containing over **800,000 employee records**. The objective is to understand how organizational, personal, and work-related factors contribute to employee burnout and attrition risk.

The dataset was sourced from **Kaggle** and stored in **MongoDB Atlas**, where it was modeled, queried, and analyzed using NoSQL principles. An interactive analytics dashboard was built using **MongoDB Atlas Charts** to visualize trends, correlations, and workforce insights.

This project was completed as part of the **ETB – Database Management Systems (DBMS)** self-study component, demonstrating the application of NoSQL data modeling and visualization techniques on a real-world HR analytics problem.

---

## Business Problem Statement

Employee burnout and high turnover lead to:

* Increased hiring and training costs
* Loss of productivity and morale
* Reduced organizational stability

By analyzing historical employee data, organizations can **identify burnout indicators early** and design data-driven HR strategies to improve employee retention and well-being.

---

## Key Business Insights

* **Burnout vs Workload:** Employees with longer working hours and high workload indicators show higher burnout levels.
* **Experience & Attrition:** Early-career employees are more prone to burnout and turnover compared to experienced employees.
* **Work-Life Balance Impact:** Poor work-life balance strongly correlates with increased burnout scores.
* **Role-Based Patterns:** Certain job roles and departments exhibit consistently higher burnout and attrition risk.
* **Predictive Value of Burnout:** Burnout score acts as a leading indicator for employee turnover probability.

These insights highlight how workforce data can support **proactive HR decision-making**.

---

## Dataset Used

**Employee Burnout and Turnover Prediction Dataset**

* **Source:** Kaggle
* **Records:** ~800,000 employees
* **Format:** CSV (ingested into MongoDB collections)

### Key Attributes

* Employee ID
* Age & Gender
* Job Role & Department
* Years of Experience
* Workload & Work-Life Balance Indicators
* Burnout Score
* Turnover / Attrition Flag

The dataset represents a realistic HR analytics scenario suitable for large-scale NoSQL analysis.

---

## Database & Data Modeling

* The dataset was stored in **MongoDB Atlas** as a document-based collection.
* Each employee record was modeled as a **single document**, allowing flexible schema evolution.
* Indexes were created on commonly queried fields such as:

  * Department
  * Job Role
  * Burnout Score
  * Attrition Flag

MongoDB’s schema-less design enabled efficient handling of a large and diverse dataset.

---

## Tools & Technologies Used

* **Data Source:** Kaggle
* **Database:** MongoDB Atlas (Cloud NoSQL Database)
* **Data Processing:** MongoDB Aggregation Framework

  * `$match`, `$group`, `$project`, `$bucket`
* **Visualization:** MongoDB Atlas Charts
* **Dashboard Link:** Public MongoDB Charts Dashboard

---

## Dashboard Overview

The MongoDB Charts dashboard provides interactive visualizations including:

* Burnout score distribution across employees
* Attrition comparison by department and role
* Work-life balance vs burnout analysis
* Experience level vs turnover probability
* Summary metrics and filtered views

The dashboard demonstrates how MongoDB Charts can be used for **HR analytics and decision support**.

---

## Learning Outcomes

Through this project, the following DBMS concepts were applied:

* NoSQL data modeling for large datasets
* Indexing strategies for analytical queries
* MongoDB aggregation pipelines for insights generation
* Building interactive dashboards for business storytelling
* Applying database concepts to real-world HR problems

---

## Conclusion

The **Employee Burnout & Turnover Prediction Analysis** project showcases how NoSQL databases like MongoDB can be effectively used for large-scale workforce analytics. By combining flexible data modeling, aggregation pipelines, and interactive dashboards, the project demonstrates the practical role of DBMS concepts in solving real organizational challenges.

This project serves as a strong example of **data-driven HR analytics using modern database technologies**.


* Make this **shorter for a strict submission limit**
* Rewrite it in a **more technical / examiner-focused tone**
* Add a **MongoDB schema + aggregation explanation section**
* Convert it into a **report-style document or PPT**

Just say the word 👍
