# Customer Segmentation and Sales Analysis

## 1. Introduction

This project presents an analysis of an online retail sales data. The analysis encompassed product performance, sales by country, customer behavior, customer segmentation, and cohort analysis.

## 2. Data Overview and Cleaning

The dataset used for this analysis is the ["online\_retail\_II.xlsx"](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset?resource=download) file from Kaggle. Initial data exploration revealed issues such as negative prices, missing values, and duplicate records. Data cleaning steps were implemented to address these issues, including:

* Removing duplicate rows.
* Handling missing values in 'CustomerID' and 'Description' columns.
* Filtering out records with negative quantity and price.
* Converting 'CustomerID' to integer type.

## 3. Insights and Recommendations

### 3.1. Product Performance

* **Top Products:** The top 10 products by sales and quantity differ, with only three products appearing in both lists. This suggests that sales volume and product popularity are not always aligned. Further investigation into the price points of these products could provide additional insights.
* **Sales Concentration:** The top 10 products account for only 10.46% of total sales. This indicates a long tail of less popular products, potentially requiring different marketing or inventory strategies.

**Recommendation:** Diversify marketing efforts beyond the top 10 products. Analyze the profitability of the long tail and consider strategies for optimizing inventory management.

### 3.2. Geographic Performance

* **Key Markets:** The UK is the primary market, followed by EIRE, the Netherlands, Germany, and France. A treemap visualization clearly highlights the UK's dominance.
* **Localized Preferences:** Each country exhibits distinct product preferences. This underscores the need for localized marketing strategies.

**Recommendation:** Tailor marketing campaigns to specific countries, highlighting products popular in each region. Further research into cultural preferences within each country can enhance these efforts.

### 3.3. Customer Behavior

* **High-Value Customers:** Top customers show a positive correlation between sales and quantity purchased. However, their purchasing patterns do not exhibit clear seasonality.
* **Geographic Concentration:** Eight out of the top ten customers are from the UK, with the Netherlands representing the second-largest customer base.

**Recommendation:** Implement loyalty programs targeted at high-value customers. Explore upselling opportunities for those customers. Analyze the UK market's high customer concentration further for potential opportunities and expansion strategies.

### 3.4. Customer Segmentation

* **Clustering Results:** K-means clustering identified three distinct customer segments based on Recency, Frequency, and Monetary Value (RFM).
  + **Cluster 2:** High-value customers with high monetary value and short recency but relatively low frequency.
  + **Cluster 1:** Low-value customers with a long recency and low frequency (single purchase).
  + **Cluster 0:** Represents the majority and remaining customers.
* **Cluster Dynamics:** Cluster 2 demonstrates stable purchasing patterns, while Cluster 1 shows a temporary uptick before ceasing activity in July 2020. This suggests the need to investigate the reasons behind Cluster 1's churn.
* **Product Preferences:** Clusters have distinct product preferences, indicating opportunities for targeted marketing.

**Recommendation:** Develop targeted marketing strategies for each cluster. Investigate the drivers of customer churn in Cluster 1 to design retention programs and potentially improve product offerings.

### 3.5. Cohort Analysis

* **Retention Trends:** Retention rates generally decline over time, but the December 2009 cohort shows significantly higher retention and re-engagement, suggesting a highly effective strategy. Conversely, several mid-2010 cohorts exhibit exceptionally low retention, particularly November 2010.
* **Cohort Performance Variation:** Significant differences in cohort performance highlight the importance of understanding the context and factors affecting customer engagement during different periods.

**Recommendation:** Analyze the December 2009 cohort to identify successful practices that could be replicated. Investigate potential causes for the lower retention in the mid-2010 cohorts, which might include external factors, changes in market conditions, or product updates. Improve initial engagement strategies to minimize early customer churn.

