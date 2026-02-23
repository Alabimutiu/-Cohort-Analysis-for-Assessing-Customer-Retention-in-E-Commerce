# 📊 Cohort Analysis for Assessing Customer Retention in the E-Commerce Industry

------------------------------------------------------------------------

## 📌 Project Overview

In this project, I delved into Cohort Analysis to gain a deeper
understanding of customer behavior. This analytical approach enabled me
to segment customers into cohorts based on their purchase behavior over
time, which was instrumental in identifying key retention opportunities
and optimizing marketing efforts. By analyzing these cohorts, I
developed strategies that helped businesses improve customer engagement
and increase the effectiveness of their marketing campaigns.

------------------------------------------------------------------------

## 🎯 Project Aim

**To conduct a retention rate time-based cohort analysis.**

The primary goal of this project was to evaluate customer retention
patterns in an e-commerce dataset by grouping customers based on their
first purchase date and tracking their behavior over time.

------------------------------------------------------------------------

## 🧭 Project Objectives

1.  **Retention Analysis**\
    To calculate and analyze the retention rates of different customer
    cohorts over time.

2.  **Cohort Segmentation**\
    To segment customers into distinct cohorts based on common
    characteristics or behaviors such as acquisition date or first
    purchase date, enabling a more granular analysis of customer
    retention.

3.  **Identify Retention Trends**\
    To identify trends and patterns in customer retention within each
    cohort.

4.  **Churn Analysis**\
    To pinpoint the timing and possible reasons for customer churn
    within various cohorts.

5.  **Recommendation Strategies**\
    To develop data-driven strategies and recommendations for improving
    customer retention based on insights gained from the cohort
    analysis.

------------------------------------------------------------------------

## 📂 Dataset Description

The dataset contains transactional e-commerce data including:

-   Customer ID\
-   Invoice Date\
-   Quantity Purchased\
-   Unit Price\
-   Country

The data was preprocessed to: - Remove canceled transactions - Handle
missing Customer IDs - Convert date columns into datetime format -
Create cohort grouping variables

------------------------------------------------------------------------

## 🛠 Tools & Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## 🔎 Methodology

### 1️⃣ Data Cleaning & Preparation

-   Removed null Customer IDs.
-   Filtered out negative quantities (returns/cancellations).
-   Converted invoice dates to datetime format.

### 2️⃣ Cohort Creation

-   Assigned each customer a **Cohort Month** based on their first
    purchase.
-   Created a **Cohort Index** representing the number of months since
    the first purchase.

### 3️⃣ Retention Matrix Construction

-   Counted unique customers per cohort per month.
-   Created a pivot table to form the cohort retention table.
-   Converted raw counts into retention percentages.

### 4️⃣ Visualization

-   Used heatmaps to visually represent customer retention over time.
-   Identified drop-offs and retention stabilization trends.

------------------------------------------------------------------------

## 📊 Key Insights

### 🔹 1. Early Customer Drop-Off

There is a significant drop in retention after the first purchase month.
This indicates that converting first-time buyers into repeat customers
is a major opportunity area.

### 🔹 2. Stabilized Retention After Month 2

Customers who make a second purchase are significantly more likely to
continue purchasing. Retention stabilizes after the initial drop.

### 🔹 3. Cohort-Based Trend Identification

Different cohorts showed varying retention performance, suggesting the
impact of: - Seasonality - Marketing campaigns - Promotional strategies

### 🔹 4. Churn Timing

Most churn occurs between Month 1 and Month 2, highlighting the
importance of early engagement strategies.

------------------------------------------------------------------------

## 💡 Strategic Recommendations

Based on the cohort analysis findings:

1.  Improve Post-Purchase Engagement (automated emails, product
    recommendations).
2.  Encourage Second Purchase (discounts, loyalty programs).
3.  Implement Customer Segmentation for personalized campaigns.
4.  Monitor retention trends using dashboards.

------------------------------------------------------------------------

## 📈 Business Impact

Cohort analysis provides a clearer picture than traditional revenue
analysis because it:

-   Tracks customer lifecycle behavior
-   Identifies churn timing
-   Measures true retention performance
-   Supports long-term revenue forecasting
-   Improves Customer Lifetime Value (CLV)

------------------------------------------------------------------------

## 🚀 Conclusion

This retention-based cohort analysis highlights that while customer
acquisition may be strong, improving early-stage retention significantly
enhances long-term profitability.

By focusing on converting first-time buyers into repeat customers,
businesses can:

-   Increase revenue sustainability\
-   Reduce customer acquisition costs\
-   Strengthen brand loyalty\
-   Improve overall marketing ROI

------------------------------------------------------------------------

## 📬 Connect With Me

If you're interested in customer analytics, retention modeling, or
data-driven growth strategies, feel free to connect with me on LinkedIn.
