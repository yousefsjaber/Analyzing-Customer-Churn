
# 📊 Analyzing Customer Churn – Data Analytics Case Study

This project analyzes customer churn for Databel using data modeling, DAX measures, exploratory data analysis, and Power BI dashboards.  
The goal is to understand why customers churn and identify patterns that can help reduce churn and improve customer retention.

---

## 🔍 1. Objectives
- Understand customer demographics and behavioral factors linked to churn.
- Analyze contract types, service usage, and payment methods.
- Identify the strongest drivers of churn.
- Build interactive Power BI dashboards to visualize churn insights.
- Provide actionable recommendations for reducing customer churn.

---

## 🧼 2. Data Preparation

The data was cleaned and prepared using the following transformations:

- Removed missing or inconsistent values
- Created calculated columns:
  - `Churned` (0/1)
  - `Churn Category`
  - `Contract Category`
  - `Age Bins`
  - `Grouped Consumption`
- Created DAX measures:
  - `Churn Rate`
  - `Number of Churned Customers`
  - `Avg Customer Service Calls`
  - `Avg Extra International Charges`
  - `Avg Extra Data Charges`

---

## 📈 3. Key Insights

### 📌 Overall Churn Rate
- Total churn rate: **26.86%**

---

### 📌 Top Churn Reasons
1. Competitor
2. Attitude
3. Dissatisfaction
4. Price
5. Other

---

### 📌 Contract Type Effect
- Month-to-Month contracts → **51% churn**
- Yearly contracts → **6.62% churn**

**Interpretation:**  
Long-term contracts help reduce churn significantly.

---

### 📌 Unlimited Plan Impact
- Unlimited customers churn more:
  - Unlimited: **32.11%**
  - Non-unlimited: **16.10%**

---

### 📌 Customer Service Calls
Customers who made more support calls are more likely to churn.

---

### 📌 Data Consumption Patterns
Low consumption customers (<5 GB) have a higher churn rate.

---

## 🗺 4. Visualizations in Dashboard
Power BI dashboard includes:

- Churn Rate by State (map)
- Churn by Age Bins
- Churn Reasons (% of total customers)
- Churn by Contract Category
- Churn by Payment Method
- Churn by Unlimited Plan
- Service Calls vs Churn Rate
- Consumption Group vs Churn
- Churn Rate by Account Length

Full visual report available in the PDF.

---

## 🛠 5. Tools Used
- **Power BI** for dashboards and modeling  
- **Python** (Pandas, NumPy, Matplotlib) for data exploration  
- **SQL** for querying datasets  
- **Excel** for pre-processing  

---

## 🧪 6. How to Run the Project
1. Open the Power BI dashboard:  
   `dashboards/churn_dashboard.pbix`
2. Read the report for conclusions:  
   `/reports/use case Analyzing Customer Churn.pdf`

---

## 📌 7. Recommendations
Based on insights:

- Encourage customers to shift to yearly contracts.
- Improve customer service experience to reduce high-call churners.
- Review pricing strategy — “Price” is a major churn reason.
- Investigate Unlimited Plan performance.
- Focus on customers with low service usage (<5GB).

---

## 🏁 8. Conclusion
This analysis provides Databel with a deep understanding of churn drivers and actionable steps to improve retention.  
The combination of data modeling, visualization, and statistical insights makes this project a strong example of applied data analytics.

---

## 👨‍💻 Author
**Yousef Jaber**  
Data Analyst | Power BI | Python | SQL  
