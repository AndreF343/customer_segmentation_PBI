# E-commerce Customer Segmentation Analysis

![image](https://github.com/user-attachments/assets/14017333-c7d6-4ce8-b227-56d56a401657)

This project analyzes customer behavior patterns in a UK-based e-commerce dataset, aiming to uncover actionable insights through customer segmentation. The dataset spans December 2010 to December 2011, with over 500,000 transactions involving approximately 4,000 customers across 38 countries.

### **Key Objectives**
- Identify distinct customer segments
- Analyze purchasing patterns
- Develop predictive models
- Provide actionable business insights

## **Table of Contents**
1. [Dataset Description](#dataset-description)
2. [Methods](#methods)
3. [Results](#results)
4. [Dashboard](#powerbi-dashboard)

## **Dataset Description**
The dataset consists of:
- **Time Period**: December 1, 2010 – December 9, 2011
- **Transactions**: 541,909 records
- **Customers**: 4,372 unique identifiers
- **Countries**: 38 regions
- **Products**: 4,070 unique items
- **Key Features**:
  - `InvoiceNo`: Unique invoice number
  - `StockCode`: Product codes
  - `Description`: Product names
  - `Quantity`: Items purchased
  - `InvoiceDate`: Date and time of transaction
  - `UnitPrice`: Price per unit in GBP
  - `CustomerID`: Unique customer identifier
  - `Country`: Customer’s location

## **Methods**
### **Preprocessing**
- Missing values handled (e.g., 24.93% missing `CustomerID` addressed).
- Cancelled orders and outliers removed.
- Derived features created (e.g., `TotalAmount`, transaction date breakdown).

### **Customer Segmentation**
- **RFM Analysis**:
  - **Recency**: Time since last purchase.
  - **Frequency**: Purchase frequency.
  - **Monetary**: Total spending.
- Clustering methods (e.g., KMeans) to group customers.

### **Predictive Modeling**
- Evaluated models such as Random Forest, Gradient Boosting, and SVM for classification tasks.

## **Results**
This analysis provides valuable insights into customer behavior and product performance for the UK-based online retail company, enabling targeted strategies for improving engagement, revenue, and retention. Key findings reveal that customer value is highly concentrated, with the top 37% of customers generating 65% of revenue. The segmentation identified "Best Customers" and "Big Spenders" as critical segments for maximizing profitability, while "Average Customers" represent a significant growth opportunity. Conversely, "Lost Customers" require intervention to mitigate revenue attrition.

The Random Forest model was selected as the most effective for customer segmentation, achieving the highest accuracy and interpretability. Feature importance analysis underscored the centrality of Recency and Monetary Value in predicting customer segments, enabling actionable insights for tailored marketing and retention strategies.

Product analysis highlighted key performance trends, including a core price range (£0.85–£3.75) and seasonal sales peaks, offering opportunities for inventory optimization and targeted promotions during high-demand periods.

### **Supported Business Actions**
**High-Value Customer Retention** Implementing a VIP program for "Best Customers" is strongly supported by the analysis, as this segment demonstrates high engagement across Recency, Frequency, and Monetary metrics. Providing exclusive benefits such as early access to new products or personalized communication can further solidify loyalty and increase long-term value.

**Churn Prevention** The importance of Recency as a predictive feature highlights the need for an early-warning system to identify at-risk customers. Using recency metrics, the company can proactively design re-engagement campaigns with personalized offers to win back disengaged customers and reduce churn.

**Inventory Optimization** Seasonal sales peaks and a concentrated core price range (£0.85–£3.75) indicate an opportunity to optimize stock levels based on demand patterns. Focusing on high-margin products during peak months (November–December) will ensure maximum revenue while minimizing overstock or stockouts.

### **PowerBI Dashboard**

![1_GO3J-OjFCxSh2r4H56_Pdw](https://github.com/user-attachments/assets/e97aebf5-e78c-47d8-9a46-472a60ef5a33)
