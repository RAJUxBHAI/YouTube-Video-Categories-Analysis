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

## Dashboard Structure & Analysis
<img width="921" height="585" alt="image" src="https://github.com/user-attachments/assets/3b556b91-d8e8-48cc-a968-0537756a17c5" />
This chart shows the distribution of employees across different departments, helping identify workforce concentration. Departments with very high employee counts indicate operational scale, while smaller departments may represent specialized or support functions. This provides baseline context for interpreting burnout and attrition trends later.

<img width="988" height="611" alt="image" src="https://github.com/user-attachments/assets/62c764c5-0a28-42c3-a88e-ffbada9d6eec" />
This line chart analyzes how average employee satisfaction varies across salary bands. It shows that satisfaction remains relatively stable across most salary ranges, with noticeable variation only at higher salary levels, suggesting that compensation alone is not the primary driver of satisfaction.

<img width="950" height="497" alt="image" src="https://github.com/user-attachments/assets/dbd5da96-39e0-4360-982f-66928c0be4c5" />
This bar chart compares employee attrition counts across departments, highlighting which departments experience the highest turnover. Departments such as Sales, Marketing, and Operations show higher attrition, indicating potential workload, pressure, or role-related stress factors.

<img width="857" height="445" alt="image" src="https://github.com/user-attachments/assets/0973d665-bdf1-42e1-a7a5-de728e9d64c7" />
This KPI-style chart presents the total workforce size (384,000 employees). It establishes the scale of the dataset and reinforces that insights are derived from a large, enterprise-level population.

<img width="929" height="510" alt="image" src="https://github.com/user-attachments/assets/ed146f04-b66d-4255-9648-b3dbe7323a90" />
This chart examines how overtime hours vary by job level. Mid-level and entry-level employees show significantly higher overtime compared to senior and leadership roles, indicating greater workload pressure on lower organizational levels.

<img width="940" height="575" alt="image" src="https://github.com/user-attachments/assets/22b00f21-c9bf-4f1e-b04c-4a70e5f2e142" />
This bar chart shows average meeting participation by job level. Leadership and senior roles participate more in meetings, while entry-level employees attend fewer meetings, reflecting role-based differences in communication and decision-making responsibilities.


<img width="955" height="462" alt="image" src="https://github.com/user-attachments/assets/91878148-31c5-4384-86e0-c2e57a59e3d3" />
This grouped bar chart compares employee satisfaction across job levels within major departments. It highlights how satisfaction varies not just by department but also by hierarchy, revealing internal disparities that could contribute to burnout risk.


<img width="829" height="578" alt="image" src="https://github.com/user-attachments/assets/d3e17bc4-e5b0-4dc8-85c3-3c2f5178beb5" />
This donut chart illustrates the proportion of employees at each job level. The workforce is heavily skewed toward mid and entry-level roles, which is important because these groups also show higher burnout and attrition risk in later analyses.


<img width="947" height="572" alt="image" src="https://github.com/user-attachments/assets/c81d1fbc-cfc3-41c6-a0ee-a4b83f8ec867" />
This chart ranks job roles based on average satisfaction scores. Creative and technical roles show relatively higher satisfaction, while administrative and support roles trend lower, indicating role-specific well-being differences.


<img width="956" height="522" alt="image" src="https://github.com/user-attachments/assets/d9130c45-7093-4a6c-ba6e-37d873ff37d0" />
This heat-style visualization displays average burnout risk by department. Departments with darker intensities represent higher burnout risk, helping identify organizational hotspots that may require HR intervention.


<img width="913" height="315" alt="image" src="https://github.com/user-attachments/assets/cd4a67e6-3d3a-4e5c-82c2-793ada342600" />
This chart analyzes how employees are distributed across burnout risk categories within each department. It shows that some departments have a higher concentration of high-risk employees even if attrition has not yet occurred.


<img width="891" height="434" alt="image" src="https://github.com/user-attachments/assets/71aae20a-6586-46b1-ad15-82e51b3e439d" />
This multivariate scatter plot examines the relationship between overtime hours, satisfaction scores, and burnout. Employees with high overtime and low satisfaction cluster around higher burnout risk, reinforcing workload as a key burnout driver.


<img width="948" height="525" alt="image" src="https://github.com/user-attachments/assets/e426133f-2d39-4525-b590-96bbd3b84f4d" />
This time-series chart tracks burnout risk and predicted turnover probability over tenure. It demonstrates that burnout often rises before turnover probability increases, validating burnout as a leading indicator of attrition.


<img width="929" height="462" alt="image" src="https://github.com/user-attachments/assets/7e7aff3f-127d-485c-9683-3dfcbb0d9991" />
This heatmap visualizes burnout risk across departments and job levels simultaneously. It helps pinpoint structural risk areas, showing that mid-level roles in certain departments consistently experience higher burnout.


Together, these 14 charts move from descriptive workforce profiling to diagnostic and predictive analysis. The dashboard demonstrates that burnout is influenced more by workload, job level, and department structure than by salary alone, and that burnout risk often precedes employee turnover.

This layered analysis supports data-driven HR decision-making by identifying where, why, and how burnout and attrition emerge within large organizations.

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

