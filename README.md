# YouTube-Video-Categories-Analysis
*(Self-Study Project for DBMS class for ETB subject)*
## Group Details
**Group 15 — Member Details**
341066 – Ramanjan Dutta 
341090 – Nandini Singh 
341077 – Mohammed Sarshad


*(Section B, PGDM-34)*

---

## Project Overview

This project focuses on analyzing **YouTube video categories metadata** to understand how content on the platform is classified and distributed across different domains such as Entertainment, Education, Music, Sports, and Technology. The dataset consists of official YouTube category information retrieved via the **YouTube Data API**, stored and analyzed using **MongoDB Atlas**.

The primary objective of the project is to demonstrate **NoSQL data modeling, aggregation, and visualization techniques** using MongoDB. The analysis and dashboard were built using **MongoDB Atlas Charts**, showcasing category distribution and assignability insights.

This project was completed as part of the **ETB – Database Management Systems (DBMS)** self-study component under the guidance of **Prof. Ashok Harnal**, FORE School of Management, New Delhi.

---

## Key Business Insights

* **Content Classification**: YouTube organizes its platform into **31 distinct content categories**, enabling structured content discovery and moderation.
* **Assignable vs Non-Assignable Categories**: Not all categories can be assigned to uploaded videos, indicating platform-level restrictions on certain content types.
* **Platform Strategy Insight**: Categories such as *Music, Film & Animation, Education,* and *Entertainment* dominate the assignable space, reflecting YouTube’s focus on mass-consumption content.
* **Data Modeling Insight**: The project highlights how **nested JSON data** from APIs can be effectively transformed and visualized using MongoDB’s aggregation framework.

---

## Tools Used

* **Data Collection**: YouTube Data API (JSON format)
* **Database**: MongoDB Atlas (Cloud-based NoSQL Database)
* **Data Processing**: MongoDB Aggregation Framework (`$unwind`, `$project`)
* **Visualization**: MongoDB Atlas Charts (Interactive Dashboard)

---

## Dataset Used

**YouTube Video Categories Dataset**

* Source: YouTube Data API
* Format: JSON
* Key Fields:

  * Category ID
  * Category Title
  * Assignable Flag

The dataset was stored as a nested document structure and later flattened using aggregation pipelines for dashboard visualization.

---

## Dashboard Overview

The MongoDB Charts dashboard provides an interactive view of:

* Distribution of YouTube video categories
* Assignable vs non-assignable category comparison
* Category-level summary metrics
* Tabular view of category metadata

The dashboard demonstrates real-world usage of **MongoDB Charts for business analytics** on semi-structured data.

*(A PDF snapshot of the dashboard is included in the repository for reference.)*

---

## Learning Outcomes

* Practical understanding of **NoSQL schema design**
* Hands-on experience with **MongoDB aggregation pipelines**
* Building dashboards from **nested JSON API data**
* Using MongoDB Atlas Charts for **business intelligence and storytelling**

---
