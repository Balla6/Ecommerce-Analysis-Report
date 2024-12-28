# E-Commerce Dataset Analysis

## **Overview**
This project analyzes a dataset from Pakistan's largest e-commerce platform (2016–2018) to uncover revenue trends, customer behavior, and product performance. The insights and recommendations aim to drive business improvement and customer engagement.

## **Goals**
- Understand revenue drivers and seasonal trends.
- Identify high-value customers and top-performing products.
- Optimize payment methods and campaign strategies.
- Explore relationships between discounts, revenue, and other factors using Python-generated visualizations.
- Demonstrate data cleaning, exploratory data analysis (EDA), and visualization skills using Python and Power BI.

## **Key Findings**
- **Total Revenue:** PKR 1,170,213,075.77.
- **Top Revenue Category:** Mobiles & Tablets (~PKR 500M).
- **Popular Payment Method:** Cash on Delivery (COD).
- **Highest Revenue Month:** November 2017.

## **Files in This Repository**
- `README.md`: Project overview and repository structure.
- `report.md`: Detailed analysis report with insights and actionable recommendations.
- `data/`: 
  - `Pakistan Largest Ecommerce Dataset.csv.zip`: The raw dataset.
  - `Cleaned_Ecommerce_Dataset.xlsx`: The cleaned and preprocessed dataset.
- `notebooks/`: 
  - `SACIP_data_loading_and_cleaning.ipynb`: Notebook for data loading, cleaning, and preprocessing.
  - `SACIP_exploratory_data_analysis.ipynb`: Notebook for exploratory data analysis (EDA) and Python visualizations.
- `visualizations/`: Saved images of Power BI visualizations and Python-generated charts.

## **Datasets**
- **Original Dataset**  
  - **File:** `Pakistan Largest Ecommerce Dataset.csv.zip`  
  - **Description:** The raw dataset containing over 1 million records of e-commerce transactions from 2016–2018. This dataset was used as the starting point for cleaning and analysis.  

- **Cleaned Dataset**  
  - **File:** `Cleaned_Ecommerce_Dataset.xlsx`  
  - **Description:** The cleaned and preprocessed version of the original dataset. This file includes only completed transactions and key features necessary for analysis after addressing missing values, removing duplicates, and filtering invalid data.

## **Visualizations**
This project includes both Python-generated charts and Power BI visualizations for comprehensive insights:

### **Power BI Dashboard**
- **Link:** [Interactive Power BI Report](https://app.powerbi.com/groups/me/reports/2d0ad03f-3a9f-47c1-857b-3e4c2ac9aa1a/59d50d94607e6d483c24?experience=power-bi)
- This dashboard provides interactive insights into revenue trends, customer behavior, and payment methods.

### **Saved Power BI Visualizations (Images):**
- `monthly_revenue_trends.png`: Monthly revenue trends (2016–2018).
- `yearly_revenue_comparison.png`: Yearly comparison of monthly revenue trends.
- `top_products_by_revenue.png`: Top products by revenue.
- `revenue_by_category.png`: Revenue by product category.
- `top_customers_by_revenue.png`: Top customers by revenue contribution.
- `customer_purchase_frequency.png`: Distribution of customer purchase frequency.
- `revenue_by_payment_method.png`: Revenue by payment method.
- `transactions_by_payment_method.png`: Number of transactions by payment method.
- `sales_by_day.png`: Sales by day of the week.

### **Python-Generated Visualizations:**
- **Revenue Distribution**: Histogram of revenue (grand total) to identify distribution patterns.
- **Top Categories and Products by Revenue**: Bar charts for high-performing categories and products.
- **Customer Purchase Frequency Analysis**: Distribution of purchase frequency, highlighting high-value customers.
- **Discount Amount vs Average Revenue (Binned)**: Bar chart showing average revenue across discount bins.
- **Quantity Ordered Distribution**: Histogram illustrating ordering patterns.
- **Correlation Heatmap**: Visualizing relationships between numeric variables.

## **How to Use**
1. **View the Analysis:**
   - Check `report.md` for detailed insights and recommendations.
   - Explore the Power BI dashboard using the link provided.

2. **Run the Python Notebooks:**
   - Use the `SACIP_data_loading_and_cleaning.ipynb` notebook to see data preprocessing steps.
   - Run the `SACIP_exploratory_data_analysis.ipynb` notebook for Python-generated EDA and visualizations.

3. **Explore the Visualizations:**
   - Access saved Power BI images in the `visualizations/` folder.
   - Use the Power BI report for interactive data exploration.

---

## **Conclusion**
This project demonstrates the use of data-driven insights to optimize business strategies and improve customer engagement. By leveraging both Python and Power BI, the analysis provides a well-rounded view of e-commerce performance and opportunities for growth.
