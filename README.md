# Online-Retail-Data-Analysis [Ongoing]

**1. Introduction**

This report presents an analysis of online retail data to identify valuable sales, products and customer segments for targeted marketing and business strategies. The analysis utilizes data cleaning, exploratory data analysis (EDA), RFM modeling, clustering techniques, Customer Lifetime Value (CLTV) analysis, and cohort analysis to uncover key insights.

**2. Data Overview and Cleaning**

The dataset used for this analysis is the ["online\_retail\_II.xlsx"](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset?resource=download) file from kaggle. Initial data exploration revealed issues such as negative prices, missing values, and duplicate records. Data cleaning steps were implemented to address these issues, including:

* Removing duplicate rows.
* Handling missing values in 'CustomerID' and 'Description' columns.
* Filtering out records with negative quantity and price.
* Converting 'CustomerID' to integer type.

**3. Exploratory Data Analysis (EDA)**

EDA was performed to understand the data's underlying patterns and trends. Key findings include:

* **Sales Trends:** Sales peak between September and December, with the highest sales occurring in November. Week 49, close to the Christmas holiday, experiences the largest sales. Customer purchasing activity is lowest on weekends, with almost no sales on Saturdays.
* **Product Performance:** The top 10 products by sales and quantity were identified, revealing potential bestsellers and high-demand items.
* **Country-wise Sales:** The UK accounts for the largest portion of sales, followed by EIRE, Netherlands, Germany, and France. Each country exhibits different top-selling products, suggesting opportunities for personalized marketing campaigns.
* **Customer Behavior:** Top customers by sales were identified, and their purchase trends were analyzed over time.

**4. Customer Segmentation**

**4.1 RFM Modeling**

RFM (Recency, Frequency, Monetary) modeling was employed to segment customers based on their purchase behavior. Customers were assigned scores for Recency, Frequency, and Monetary value, and these scores were combined to create segments such as "Champions," "Loyal Customers," and "Potential Loyalists."

**4.2 Clustering**

K-means clustering was applied to segment customers based on their RFM values. The Elbow method was used to determine the optimal number of clusters (k). Customers were assigned to clusters based on their similarity in RFM characteristics.

**5. Customer Lifetime Value (CLTV) Analysis**

CLTV analysis was conducted to estimate the total revenue a customer is expected to generate over their lifespan. Average purchase value, average purchase frequency, and an estimated customer lifespan were used to calculate CLTV for each customer segment. The analysis revealed the most valuable customer groups in terms of long-term revenue potential.

**6. Cohort Analysis**

Cohort analysis was performed to track the behavior of customer groups acquired at different times. Cohorts were defined based on the month of the customer's first purchase. Retention rates were calculated and visualized using a heatmap to understand how customer behavior changes over time.

**7. Results and Insights**

* **RFM Segmentation:** The RFM model revealed the distribution of customers across different segments, highlighting valuable customer groups such as "Champions" and "Loyal Customers."
* **Clustering Segmentation:** Clustering analysis provided further granularity by grouping customers based on their RFM profiles. The analysis of cluster characteristics identified distinct customer behaviors and purchase patterns.
* **Sales Trends:** Sales trends were analyzed by segment and cluster, revealing variations in purchase patterns over time.
* **Product Preferences:** Top products purchased by each segment and cluster were identified, providing insights for targeted product recommendations.
* **CLTV Insights:** CLTV analysis identified the customer segments with the highest long-term revenue potential, enabling prioritization of marketing efforts.
* **Cohort Analysis:** Cohort analysis revealed trends in customer retention and provided insights into how customer behavior evolves over time.

**8. Recommendations**

Based on the analysis, the following recommendations are proposed:

* **Targeted Marketing:** Develop personalized marketing campaigns for each customer segment and cluster, focusing on their specific needs and preferences.
* **Product Recommendations:** Utilize product preference insights to offer targeted product recommendations to customers, enhancing cross-selling and upselling opportunities.
* **Customer Retention:** Implement strategies to retain valuable customer segments, such as loyalty programs and personalized offers.
* **Customer Acquisition:** Explore opportunities to acquire new customers with similar characteristics to existing high-value segments.
* **CLTV Optimization:** Focus on acquiring and retaining customers from high-CLTV segments to maximize long-term revenue.
* **Cohort-Based Engagement:** Develop targeted engagement strategies for different cohorts based on their retention patterns.
* **Further Analysis:** Conduct deeper analysis of customer demographics, browsing behavior, and other data points to further refine segmentation strategies.

**9. Conclusion**

This analysis has provided valuable insights into online retail customer behavior and segmentation. By leveraging these insights, businesses can develop targeted strategies to improve customer relationships, optimize marketing efforts, and drive business growth. Continued analysis and refinement of segmentation approaches will be crucial for maximizing customer lifetime value and achieving long-term success.
