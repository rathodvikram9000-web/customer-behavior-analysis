# Customer Behavior Analysis

## 📌 Project Overview
This project analyzes **customer shopping behavior** using an end-to-end data analytics pipeline.  
The objective is to understand how **customer demographics, discounts, subscriptions, purchase frequency, shipping type, and seasonality** influence purchasing behavior and revenue.

The project follows a real-world analytics workflow:
**Python → MySQL → Power BI**

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, SQLAlchemy) – Data cleaning, EDA, feature engineering
- **MySQL** – Business-focused analytical SQL queries
- **Power BI** – Interactive dashboard & KPI visualization
- **GitHub** – Version control and documentation

---

## 📂 Dataset Information
- **Source:** Kaggle – Customer Shopping Behavior Dataset
- **Records:** ~3,900 customers
- **Key Features:**
  - Customer demographics (Age, Gender, Location)
  - Product details (Category, Item, Size, Color)
  - Purchase amount & review ratings
  - Discounts & promo usage
  - Subscription status
  - Shipping type & purchase frequency
  - Seasonal purchase patterns

---

## 🐍 Python Analysis
- Loaded and explored the dataset using Pandas
- Generated summary statistics and checked missing values
- Cleaned and standardized column names
- Engineered new features:
  - Age groups
  - Numeric purchase frequency
- Prepared clean data for SQL and Power BI
- Exported processed data to MySQL using SQLAlchemy

---

## 🗄️ SQL Analysis (MySQL)
- Wrote **20+ business-focused SQL queries**
- Performed customer segmentation using `CASE WHEN`
- Identified repeat and loyal customers
- Analyzed:
  - Revenue by gender
  - Discount vs spending behavior
  - Subscription impact
  - Season-wise and category-wise revenue
- Used subqueries and window functions for deeper insights

---

## 📊 Power BI Dashboard
Created an interactive **Customer Behavior Dashboard** featuring:
- KPI cards (Customers, Avg Purchase Amount, Avg Rating, Discount Dependency)
- Category-wise and season-wise revenue trends
- Age group and item-level analysis
- Interactive slicers for gender, subscription, and shipping type

[[![Power BI Dashboard](images/powerbi_dashboard.png)](https://github.com/rathodvikram9000-web/customer-behavior-analysis/commit/6c1be9d22e1b66fd4e0e750388ed59a0c2ec1683)](https://github.com/rathodvikram9000-web/customer-behavior-analysis/blob/main/powerbi_dashboard.png)


---

## 🔍 Key Insights
- Clothing is the highest revenue-generating category
- Subscribers show higher engagement despite being fewer
- Discounts increase purchase frequency but not always revenue
- Seasonal trends significantly affect sales
- Loyal customers contribute disproportionately to revenue

---

## 📁 Project Structure
customer-behavior-analysis/
├── dataset/
├── python/
├── sql/
├── powerbi/
├── images/
└── README.md


---

## 👤 Author
**Vikram Rathod**  
Aspiring Data Analyst | Python | SQL | Power BI
