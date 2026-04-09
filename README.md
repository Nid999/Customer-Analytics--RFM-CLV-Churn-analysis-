# Customer-Analytics--RFM-CLV-Churn-analysis 


# Project Overview
This project focuses on analyzing customer behavior using RFM Analysis (Recency, Frequency, Monetary),Customer Lifetime Value (CLV), and Churn Analysis.

The objective is to transform raw transactional data into actionable business insights that can support customer retention strategies, segmentation, and revenue growth.

 # Dataset
- Brazilian E-commerce Dataset (~99,000 records)
- Data includes:
  - Customer details
  - Orders & transactions
  - Payments & order value


# Tools & Technologies Used
- **SQL (MySQL Workbench)** → transformation and feature engineering  
- **Power BI** → Data cleaning,Data visualization & dashboard building  
- **Excel/CSV** → Data handling & import 

# Data Processing Steps

1. Data Cleaning
- Removed null and invalid values
- Handled large dataset efficiently using powerBI
- Ensured proper data types (date, numeric, text)

 2. Data Transformation
- Merged multiple tables:
  - Orders
  - Order Items
  - Payments
  - Customers
- Created a consolidated dataset:Customer_unique_id, order_id, total_order_value, date, etc.



# Feature Engineering

#🔹 RFM Metrics
- **Recency** → Days since last purchase  
- **Frequency** → Number of orders  
- **Monetary** → Total spend  

### 🔹 RFM Segmentation
| Score Range | Segment     |
|------------|------------|
| 13+        | VIP        |
| 10–12      | Loyal      |
| 7–9        | Potential  |
| 4–6        | At Risk    |
| <4         | Lost       |

---

# CLV (Customer Lifetime Value)
- Estimated using:CLV = Avg Order Value × Purchase Frequency × 12
- 
  

# Churn Analysis
- Customers inactive for >90 days classified as:
  - **Churned**
  - **Active**

---

## Dashboard Features

## 🔹 KPI Cards
- Total Revenue → 15.84M
- Total Customers → 96K
- Avg CLV → 19.72
- Churn Rate → 45.18%

---

##🔹 Visualizations
- Customer Distribution by RFM Segment
- Revenue Contribution by Segment
- Churn Analysis 
- CLV Segmentation
- Customer-Level Table

---

##  Key Insights

- **Potential customers are highest in number**, indicating strong growth opportunity
- **At Risk customers contribute significant revenue** → require retention strategies
- **High churn rate (~45%)** highlights need for engagement improvement
- **VIP customers are low but high-value** → should be prioritized

---

## Business Recommendations

-  Target "At Risk" customers with retention campaigns  
- Focus on VIP customers for loyalty programs  
- Convert Potential → Loyal customers through engagement  
- Reduce churn via personalized marketing  

---


---

### Churn Analysis
- Customers inactive for >90 days classified as:
  - **Churned**
  - **Active**

---

## Dashboard Features

### 🔹 KPI Cards
- Total Revenue → 15.84M
- Total Customers → 96K
- Avg CLV → 19.72
- Churn Rate → 45.18%

---

### 🔹 Visualizations
- Customer Distribution by RFM Segment
- Revenue Contribution by Segment
- Churn Analysis (Pie Chart)
- CLV Segmentation
- Customer-Level Table

---

##  Key Insights

- **Potential customers are highest in number**, indicating strong growth opportunity
- **At Risk customers contribute significant revenue** → require retention strategies
- **High churn rate (~45%)** highlights need for engagement improvement
- **VIP customers are low but high-value** → should be prioritized

---

##  Business Recommendations

- Target "At Risk" customers with retention campaigns  
-  Focus on VIP customers for loyalty programs  
-  Convert Potential → Loyal customers through engagement  
-  Reduce churn via personalized marketing  

---




## Author
**Nidhi Shree**  
MBA (Marketing & Business Analytics) | Aspiring Data Analyst  

---

## 🔗 Connect with Me
(https://www.linkedin.com/in/nidhi-shree-7a3820257)



