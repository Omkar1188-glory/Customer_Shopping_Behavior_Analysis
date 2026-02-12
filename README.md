# 🛍️ Customer Shopping Behavior Analysis  
### End-to-End Data Analytics Project  
**Author:** Omkar Kadam  
**Tools Used:** Python | MySQL | Power BI | SQLAlchemy | Excel

---

## 📌 Project Overview

The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw transactional data into strategic business intelligence by:

- **Data Preparation, Modeling & Exploratory Data Analysis (Python)**  
- **Data Analysis (MySQL)**  
- **Visualization & Insights (Power BI)**  
- **Report & Presentation**

---

## 🗂️ Dataset Summary

- 3,900 customer transactions  
- 18 columns  
- Demographics: Age, Gender, Location  
- Purchase Details: Item, Category, Purchase Amount  
- Behavioral Data: Previous Purchases, Discount Applied, Review Rating  
- 37 missing values in `review_rating` handled using median imputation  

---

## 🔄 Project Workflow

Raw Dataset  
↓  
Python (Cleaning & Feature Engineering)  
↓  
MySQL (Data Storage & SQL Analysis)  
↓  
Power BI (Dashboard & Visualization)  
↓  
Business Insights & Recommendations  

---

# 🛠️ How to Use This Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

---

## 2️⃣ Open the Jupyter Notebook

Open:

`Customer_Shopping_Behavior_Analysis.ipynb`

This notebook contains:

- Data Import  
- Data Exploration  
- Missing Value Handling  
- Feature Engineering  
- SQL Database Connection (SQLAlchemy)  
- Data Loading into MySQL  

---

## 3️⃣ Load Data into SQL Database

Create a database in MySQL:

```sql
CREATE DATABASE customer_behavior;
```

Update database credentials inside the notebook.

Run the notebook to push cleaned data into MySQL.

Verify table creation:

```sql
SHOW TABLES;
SELECT * FROM customers LIMIT 10;
```

---

## 4️⃣ Run SQL Business Queries

Open:

`customer_behavior_sql_queries.sql`

This file answers business questions such as:

- Revenue by Gender  
- High-Spending Discount Users  
- Top 5 Products by Rating  
- Shipping Type Comparison  
- Subscriber vs Non-Subscriber Analysis  
- Customer Segmentation (New / Returning / Loyal)  
- Top 3 Products per Category (Window Functions)  
- Repeat Buyers vs Subscription Behavior  
- Revenue Contribution by Age Group  

Run queries inside MySQL Workbench.

---

## 5️⃣ Connect MySQL to Power BI

Open:

`customer_behavior_dashboard.pbix`

Then:

- Click **Get Data → MySQL Database**
- Server: `localhost`
- Database: `customer_behavior`
- Load `customers` table
- Build interactive visuals

---

## 6️⃣ Create Project Report & Presentation

- Prepare structured project report (PDF)
- Build presentation deck (PowerPoint)
- Highlight business insights and recommendations
- Present end-to-end workflow clearly

---

# 📊 Key Insights

- Male customers generated higher total revenue.
- Loyal customers represent the largest segment.
- Express shipping users spend slightly more than standard users.
- Non-subscribers generate higher total revenue.
- Young adults contribute the highest revenue share.
- Certain products show high discount dependency.

---

# 💡 Business Recommendations

- Increase subscription incentives for repeat buyers.
- Develop structured loyalty programs.
- Focus marketing on high-revenue categories.
- Target high-spending age groups.
- Optimize discount strategy to protect margins.

---

# 📜 License

MIT — feel free to fork, star ⭐

---

# 👨‍💻 About the Author

**Omkar Kadam**  
Aspiring Data Analyst / Data Scientist  

📌 LinkedIn: https://linkedin.com/in/omkar-kadam-5b493b298  
📧 Email: Omkar78789@gmail.com  
📍 Location: Mumbai, India  
