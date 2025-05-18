# Capstone Data Collection – Step 2: Collect Your Data

## ✅ Overview

This notebook explores two publicly available datasets relevant to operations and efficiency work at Fastenal, aligning with my role in operations development. The analysis focuses on user behavior in e-commerce and shipment logistics to simulate real-world decision-making scenarios around delivery timing and user activity.

---

## 📊 Datasets Explored

### 1. Worker Productivity Dataset
- **Filename:** `worker_productivity_data.csv`
- **Source:** [Kaggle - Ecommerce Behavior Data from Multi-Category Store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
- **Description:** Captures user behavior on an e-commerce platform including view, cart, and purchase actions.
- **Rows Used:** 1,099 (manually trimmed for performance)
- **What I Did:**
  - Parsed `event_time` column as datetime.
  - Visualized user activity per day.
  - Calculated session gaps using `diff()` by `user_id`.
  - Identified top 10 most active users.

---

### 2. Supply Chain Shipment Data
- **Filename:** `Train.csv`
- **Source:** [Kaggle - Late Deliveries (Customer Analytics)](https://www.kaggle.com/datasets/prachi13/customer-analytics)
- **Description:** Shipment records with info on delivery mode, customer ratings, product cost, and delivery outcomes.
- **What I Did:**
  - Explored how weight, cost, and discount affect delivery delays.
  - Created a correlation heatmap of numerical fields.
  - Grouped by `Delivered_On_Time` and calculated means to uncover trends.

---

## 🧠 Why These Datasets?
These datasets simulate key decision-making areas in supply chain and operations:
- How customer behavior patterns relate to session productivity and conversion.
- How logistics metrics (e.g., cost, weight, and discounts) correlate with fulfillment performance.

---

## 📁 Files in This Repository
- `Mini_Project.ipynb`: Jupyter Notebook with full code, visuals, and markdown documentation.
- `worker_productivity_data.csv`: Trimmed behavioral dataset for productivity exploration.
- `Train.csv`: Shipment dataset used for logistics and delivery delay analysis.

---

## 📌 Notes
- All data is public and sourced from Kaggle.
- This work is part of the UMass Global Data Analytics Capstone project – Step 2: Data Collection.
