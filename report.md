# **E-Commerce Dataset Analysis Report**

---

## **1. Introduction**
This analysis focuses on a dataset from Pakistan's largest e-commerce platform (2016–2018), containing over 1 million records. The primary objectives of the project were to:
- Uncover revenue trends, customer behavior, and product performance.
- Identify top revenue-generating products, categories, and customer segments.
- Provide actionable insights to improve business performance.

---

## **2. Data Preparation**
### **Initial Dataset Overview**
- **Total Rows:** 1,048,575.
- **After Cleaning:** 233,635 rows (focused on "completed" orders).

### **Key Cleaning Steps**
- Removed irrelevant columns and duplicates.
- Addressed missing values in critical fields (e.g., `grand_total`, `category_name_1`).
- Filtered for valid and completed transactions only.

---

## **3. Exploratory Data Analysis (EDA)**

### **3.1 Revenue Trends**
- **Total Revenue:** PKR 1,170,213,075.77.
- **Monthly Revenue Trends:**
![Monthly Revenue Trends]("C:/Users/balla/Downloads/monthly_revenue_trends.png")
  - Revenue peaked in **November 2017** and **January 2018**.
  - Sharp dips observed in **April 2018** and **June 2018**.
  - Possible causes for spikes include **Black Friday campaigns** and **seasonal sales**.
- **Yearly Comparison:**
  - Revenue growth in **2018** was strong in the first half but declined later.

### **3.2 Product and Category Analysis**
- **Top Revenue-Generating Categories:**
  - **Mobiles & Tablets:** PKR 500 million.
  - Other top categories: Appliances, Entertainment, and Women’s Fashion.
- **Low-Performing Categories:**
  - Books, Kids & Baby, and School & Education generated minimal revenue.
- **Top Products:**
  - SKU: `MATSAM59DB75ADB2F80` generated **PKR 32.8 million**.
  - Other notable products include `IDROID_BALRX7-Gold` and `MATSAM59DB757FB47A2`.

### **3.3 Customer Segmentation**
- **Unique Customers:** 67,093.
- **Average Order Value (AOV):** PKR 5,008.72.
- **Top Revenue-Generating Customers:**
  - Customer ID: `50387` contributed **PKR 35.7 million**.
- **High-Frequency Customers:**
  - 3,034 customers made more than **10 purchases**.
- **Customer Segmentation Insights:**
  - A few customers contributed disproportionately high revenue, indicating significant spending by a small segment.

### **3.4 Payment Method Analysis**
- **Most Used Payment Methods:**
  - **Cash on Delivery (COD):** Majority of transactions (~63%).
- **Highest Revenue Payment Methods:**
  - COD generated **PKR 393 million**, followed by Easypay Voucher (**PKR 282 million**).

### **3.5 Sales Timing Analysis**
- **Day of the Week Analysis:**
  - **Friday** had the highest sales.
- **Monthly Growth Analysis:**
  - **Top Months for Growth:**
    - November 2017: **1339% growth**.
    - July 2018: **930% growth**.
  - **Lowest Months for Growth:**
    - June 2018: **-99.9% growth**.
    - December 2017: **-93.5% growth**.

---

## **4. Actionable Insights**
### **Product Optimization**
- Focus on **Mobiles & Tablets**, Appliances, and Entertainment for inventory management and marketing efforts.
- Reassess the feasibility of underperforming categories like **Books** and **School & Education**.

### **Customer Retention**
- Leverage loyalty programs for high-frequency and high-value customers.
- Target campaigns to high-spending customers like **Customer ID: 50387**.

### **Marketing & Campaign Strategy**
- Concentrate major campaigns in months with historically high sales (**November**, **January**, and **July**).
- Analyze and address reasons for revenue decline in **June 2018** to prevent future losses.

### **Payment Method Optimization**
- Encourage the use of digital payment methods like **Easypay Voucher**, which generated significant revenue.
- Provide incentives for customers to switch from COD to digital methods to reduce operational risks.

### **Promotions & Seasonal Planning**
- Align promotional activities with revenue peaks (e.g., Black Friday and holiday seasons).
- Explore opportunities to boost sales on low-revenue days like **Sunday** and during slow months.

### **Categorization and Classification**
- Resolve the issue of **uncategorized products (\N)**, which contributed over **PKR 17.8 million** in revenue.

---

## **5. Conclusion**
The analysis uncovered key revenue drivers, identified top-performing products and customers, and provided a comprehensive understanding of customer behavior. These findings can guide targeted marketing efforts, product strategies, and operational improvements to maximize profitability.

---


