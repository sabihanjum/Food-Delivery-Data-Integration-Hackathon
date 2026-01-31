# Food Delivery Data Integration & Analysis

This project was developed as part of a data analytics hackathon.  
It demonstrates real-world data integration using multiple file formats
(CSV, JSON, and SQL) and performs analytical insights on food delivery data.

---

## Datasets Used
- **orders.csv** – Transactional order data
- **users.json** – User master data (city, membership)
- **restaurants.sql** – Restaurant master data (cuisine, rating)

---

## Data Integration
- Joined datasets using **LEFT JOIN**
- Join keys:
  - orders.user_id → users.user_id
  - orders.restaurant_id → restaurants.restaurant_id
- Final dataset contains **10000 rows** (one row per order)

---

## Analysis Performed
- Gold vs Regular user behavior
- Repeat users and high spenders
- City-wise and cuisine-wise revenue
- Rating-based performance
- Seasonal revenue trends
- MCQs, numerical questions, and fill-in-the-blanks derived from the final dataset

---

## How to Run
1. Ensure Python is installed
2. Install required libraries:
   ```bash
   pip install pandas
