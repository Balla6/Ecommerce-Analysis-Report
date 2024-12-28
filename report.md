# E-Commerce Dataset Analysis Report

## **1. Introduction**
This project analyzes a dataset from Pakistan's largest e-commerce platform (2016–2018), containing over 1 million records. The primary goals were to:
- Uncover revenue trends, customer behavior, and product performance.
- Identify top revenue-generating products, categories, and customer segments.
- Provide actionable recommendations to improve business performance.

---

## **2. Data Preparation**
### Dataset Overview
- **Initial Dataset Size:** 1,048,575 rows, 26 columns.
- **Cleaned Dataset Size:** 233,635 rows, 15 columns.

### Cleaning Steps
1. **Removed irrelevant columns:** Dropped redundant and unnecessary fields like `increment_id`, `sales_commission_code`, and unnamed columns.
2. **Addressed missing values:** Retained rows where critical fields (e.g., `created_at`, `grand_total`) were not null.
3. **Removed duplicates:** Ensured unique rows for analysis.
4. **Filtered for completed orders:** Focused on transactions marked as `complete`.

---

## **3. Exploratory Data Analysis (EDA)**

### **3.1 Revenue Trends**
#### **Chart: Monthly Revenue Trends (2016–2018)**
- **Insight:** November 2017 recorded the highest revenue (~PKR 328M), likely due to Black Friday campaigns. January 2018 also showed high revenue (~PKR 311M) due to holiday shopping.
- **Observation:** Revenue declined significantly in April 2018 (~PKR 45M) and June 2018 (~PKR 6M), highlighting potential seasonal factors.

**Actionable Recommendations:**
1. Prioritize campaigns in high-revenue months like November and January.
2. Investigate reasons for April and June dips and design strategies to address these gaps.

---

#### **Chart: Yearly Comparison of Monthly Revenue Trends**
- **Insight:** November 2017 dominated as the top revenue month, reinforcing the effectiveness of Black Friday sales.
- **Observation:** Revenue grew year-over-year in December (from PKR 21M in 2016 to PKR 91M in 2017), showcasing improved campaigns.

**Actionable Recommendations:**
1. Expand Black Friday campaigns to other months or categories.
2. Launch new campaigns during traditionally low-revenue months like June to September.

---

### **3.2 Product and Category Insights**
#### **Chart: Revenue by Product Category**
- **Insight:** Mobiles & Tablets led with PKR 500M, followed by Appliances (PKR 178M) and Entertainment (PKR 155M).
- **Observation:** Categories like Books (PKR 1M) and School & Education (PKR 2M) had minimal contributions.

**Actionable Recommendations:**
1. Invest more in high-performing categories (Mobiles & Tablets, Appliances).
2. Reassess underperforming categories to identify improvement areas.

---

#### **Chart: Top 10 Products by Revenue**
- **Insight:** The top product generated PKR 32.8M, significantly outperforming others.
- **Observation:** The top three products contributed disproportionately to overall revenue.

**Actionable Recommendations:**
1. Bundle top-performing products with complementary items to maximize revenue.
2. Investigate marketing strategies for lower-performing products to boost their sales.

---

### **3.3 Customer Insights**
#### **Chart: Distribution of Customer Purchase Frequency**
- **Insight:** Most customers (138K) made 1–10 purchases, indicating a reliance on occasional buyers.
- **Observation:** High-frequency customers (>50 purchases) contributed significantly to revenue despite being a smaller group.

**Actionable Recommendations:**
1. Design loyalty programs targeting high-frequency customers.
2. Create engagement campaigns to convert occasional buyers into repeat customers.

---

#### **Chart: Top 10 Customers by Revenue**
- **Insight:** Customer 50387 contributed ~PKR 35.8M, far outpacing the next highest customer.
- **Observation:** The top 10 customers accounted for a significant share of overall revenue.

**Actionable Recommendations:**
1. Provide exclusive perks to top customers to ensure retention.
2. Expand the spending potential of other high-value customers through personalized recommendations.

---

### **3.4 Advanced Insights**
#### **Chart: Discount Amount vs Revenue**
- **Insight:** Discounts don’t consistently lead to proportional increases in revenue.
- **Observation:** There’s a threshold where additional discounts stop significantly impacting revenue growth.

**Actionable Recommendations:**
1. Test the impact of varying discount thresholds to optimize profitability.
2. Focus on targeted discounts for high-value customers.

---

#### **Chart: Distribution of Quantity Ordered**
- **Insight:** Most orders involve single items, with very few bulk purchases.
- **Observation:** The skewed distribution suggests opportunities to promote bulk orders.

**Actionable Recommendations:**
1. Offer bundle deals or incentives for higher quantities ordered.
2. Introduce free shipping thresholds to encourage bulk purchases.

---

#### **Chart: Correlation Heatmap**
- **Insight:** A strong correlation exists between `qty_ordered` and `grand_total` (0.88).
- **Observation:** Increasing order quantities directly impacts total revenue.

**Actionable Recommendations:**
1. Leverage the correlation by promoting higher quantities per order.
2. Create upselling opportunities during checkout to encourage more purchases.

---

### **3.5 Payment Insights**
#### **Chart: Revenue by Payment Method**
- **Insight:** Cash on Delivery (COD) led with PKR 393M, followed by Easypay Voucher (PKR 283M).
- **Observation:** Digital payment methods are gaining traction but remain secondary to COD.

**Actionable Recommendations:**
1. Encourage digital payment adoption through cashback or discounts.
2. Gradually introduce nominal charges for COD to incentivize prepaid options.

---

#### **Chart: Number of Transactions by Payment Method**
- **Insight:** COD accounted for the majority of transactions (148K), while digital wallets like Payaxis had moderate usage (23K).
- **Observation:** Less popular methods like UBL credit card contributed minimally.

**Actionable Recommendations:**
1. Focus on transitioning COD users to digital payment methods.
2. Streamline payment options by removing underperforming methods.

---

### **3.6 Sales Timing Insights**
#### **Chart: Sales by Day of the Week**
- **Insight:** Friday recorded the highest revenue (~PKR 332M), likely due to payday effects or weekly promotions.
- **Observation:** Sunday had the lowest sales (~PKR 120M), indicating reduced customer activity.

**Actionable Recommendations:**
1. Launch exclusive Friday campaigns to capitalize on high sales activity.
2. Boost weekend engagement through targeted Sunday promotions.

---

## **4. Recommendations Summary**
1. **Seasonal Campaigns:** Focus on November and January for peak revenue and develop strategies for slow months like June.
2. **Customer Retention:** Implement loyalty programs for repeat customers and engagement strategies for occasional buyers.
3. **Product Strategy:** Prioritize investment in Mobiles & Tablets while reassessing underperforming categories.
4. **Discount Strategies:** Optimize discounting thresholds to balance revenue and profitability.
5. **Payment Optimization:** Encourage digital payment adoption to reduce operational risks.
6. **Sales Timing:** Use data-driven insights to plan campaigns around high-activity days and months.

---

## **5. Conclusion**
This analysis uncovered key drivers of revenue, product performance, and customer behavior. The actionable recommendations provide a roadmap for improving profitability, optimizing campaigns, and driving customer engagement.
