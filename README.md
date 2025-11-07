
---


# 🍕 Pizza Sales Analysis – 2015 Dataset

## 📊 Project Overview

This project focuses on analyzing **Pizza Sales Data (2015)** to understand business performance, customer trends, and product popularity.
The analysis was performed using **SQL**, **Python (Jupyter Notebook)**, and **Power BI** to deliver both **data insights** and **interactive visual dashboards**.

---

## 🎯 Objectives

The goal of this analysis was to:

* Identify key **sales performance indicators (KPIs)**.
* Discover **daily and monthly sales trends**.
* Analyze **pizza category and size contributions**.
* Highlight **top and worst performing pizzas** based on revenue, quantity, and orders.
* Build a **Power BI dashboard** for real-time and visual understanding.

---

## 🧩 Dataset

* **Name:** Pizza Sales Dataset (2015)
* **Source:** Kaggle
* **Description:** Contains details of all pizza orders including order ID, date, time, pizza name, size, category, quantity, price, etc.

| Column Name    | Description                                    |
| -------------- | ---------------------------------------------- |
| order_id       | Unique identifier for each order               |
| date           | Date of order                                  |
| time           | Time of order                                  |
| pizza_id       | Unique pizza identifier                        |
| pizza_name     | Name of the pizza                              |
| pizza_category | Type of pizza (Classic, Supreme, Veggie, etc.) |
| pizza_size     | Size (S, M, L, XL, XXL)                        |
| quantity       | Number of pizzas ordered                       |
| unit_price     | Price of one pizza                             |
| total_price    | Total price for the order                      |

---

## 🧠 Analysis Process

### 1️⃣ **Data Exploration with SQL**

* Connected to the database and executed SQL queries to:

  * Calculate total revenue, total orders, and total pizzas sold.
  * Identify best and worst performing pizzas.
  * Find monthly and daily order trends.
* Exported results to CSV for further analysis in Jupyter Notebook and Power BI.

### 2️⃣ **Data Cleaning and Analysis in Python (Jupyter Notebook)**

* Loaded data using **pandas**.
* Checked for missing values, duplicates, and data consistency.
* Converted date/time columns to proper datetime formats.
* Performed **groupby()**, **pivot_table()**, and **visualizations** using matplotlib/seaborn to validate SQL insights.

### 3️⃣ **Data Visualization in Power BI**

Created a **two-page interactive dashboard**:

#### 📄 Page 1 – KPI Overview

* Total Revenue
* Average Order Value
* Total Pizzas Sold
* Total Orders
* Average Pizzas per Order
* Daily and Monthly Trends
* % Sales by Pizza Category
* % Sales by Pizza Size

#### 📄 Page 2 – Pizza Performance Insights

* Top 5 and Bottom 5 Pizzas by:

  * Total Revenue
  * Quantity Sold
  * Total Orders

---

## ⚙️ Tools and Technologies

| Tool                                     | Purpose                            |
| ---------------------------------------- | ---------------------------------- |
| **SQL (MySQL / SQLite)**                 | Data extraction and validation     |
| **Python (Pandas, Matplotlib, Seaborn)** | Data cleaning and EDA              |
| **Power BI**                             | Dashboard design and visualization |
| **Jupyter Notebook**                     | Analysis and documentation         |
| **Excel / CSV**                          | Data storage and exports           |

---

## 📈 Key Insights

* **Highest revenue** generated in **July** and **December**.
* **Large (L)** size pizzas contributed the most to sales.
* **Classic** and **Supreme** categories were the top-performing types.
* A few pizzas accounted for a **large share of total revenue** (Pareto principle).
* Identified **top 5 best** and **worst 5 pizzas** for decision-making.

---

## 📚 Learning Outcomes

* Improved understanding of **data storytelling** and **KPI reporting**.
* Strengthened **SQL querying** and **data validation** techniques.
* Gained hands-on experience in **Power BI dashboard creation**.
* Learned the importance of combining **technical accuracy with visual clarity**.

---

## 🧩 Future Enhancements

* Automate daily refresh using Power BI service.
* Add customer segmentation and time-based forecasting.
* Integrate Power BI with a live SQL database connection.

---

## 👨‍💻 Author

**Arafath J**
📍 Data Science Enthusiast | SQL | Power BI | Python
🔗 [LinkedIn](https://www.linkedin.com/in/arafath-j-37b0bb221/) • [GitHub](github.com/ArafathJ/)

---

