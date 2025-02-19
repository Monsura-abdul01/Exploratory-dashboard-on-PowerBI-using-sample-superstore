
# Sample superstore Analysis(E-commerce)

## Table of contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)

### Project Overview

The Sample Superstore project focuses on creating exploratory dashboards with Power BI to analyze and visualize key performance indicators (KPIs). The dashboard provides insights into sales performance, product metrics, shipping efficiency, and customer segmentation. 
By leveraging data from the superstore, the project aims to uncover hidden patterns and trends that can drive strategic business decisions. 
The visualizations transform raw data into clear, actionable insights, enabling better decision-making and operational improvements. 
This project highlights the power of data storytelling and its impact on business growth.

### Data Sources

The primary dataset used for this analysis is a comprehensive collection of sales, product, shipping, and customer information from the Sample Superstore. 
This dataset includes detailed records on transactions, product categories, shipping methods, customer demographics, and regional sales performance. 

### Tools

- **Power Query**: Used for efficient data transformation, cleansing, and preparation, ensuring that the data is in the best possible shape for analysis.
    - [Download here](www.microsoft.com)
- **Power BI**: Utilized for comprehensive data analysis and visualization, enabling the creation of interactive and insightful dashboards that drive business decisions.

### Data cleaning/Preparation

Data cleaning and preparation are crucial steps to ensure the accuracy and reliability of the analysis. The following tasks were performed at initial stage;

1. **Removing Duplicates**: Identifying and eliminating duplicate records to avoid redundancy and ensure data integrity.
2. **Standardizing Data Formats**: Ensuring consistency in data formats, such as dates, currency, and categorical variables, to facilitate accurate analysis.
3. **Correcting Errors**: Identifying and correcting any inaccuracies or inconsistencies in the dataset, such as typos, incorrect values, or misclassified entries.
4. **Filtering and Validating Data**: Filtering out irrelevant or outlier data points that could skew the results, and validating the accuracy and reliability of the remaining data.
6. **Data Transformation**: Using Power Query to transform raw data into a structured format suitable for analysis, including operations like pivoting, merging, and aggregating data.

By thoroughly cleaning and preparing the data, we can ensure that the resulting analysis and insights are based on high-quality, accurate information.

### Exploratory data Analysis

- What is the overall sales trend over the given time period?
- Which periods have the highest sales ?
- How does the sales performance vary by product category?
- How can customers be segmented based on their purchasing behavior and demographics?
- What are the shipping costs and efficiency for different shipping methods?

### Findings
Here's a summary of the analysis results:

**Sales Performance**
- Sales have steadily increased over the years.
- The central region has the highest number of sales, particularly for technology products.
- The first quarter has the lowest turnover, while the fourth quarter boasts the highest sales.

**Product Performance**
- The quantity of orders has significantly increased over the years.
- On average, 13.81 office supplies are ordered, with approximately 436 returns.
- Both technology and furniture categories have similar average quantities ordered as office supplies but experience higher returns, averaging 1,500 and 1,600 respectively.
- Technology products have the highest number of sales.

**Shipping Performance**
- Delivery trucks incur the highest freight costs and average freight costs, primarily due to transporting jumbo boxes and jumbo drums.
- Regular air shipments handle the highest volume of goods and have the lowest average freight cost.
- Express air has the second-highest freight cost but ships the least number of goods.
- There is no clear reason for the high average freight cost of express air shipments, unlike delivery trucks, which have high costs due to the type of goods shipped.

**Customer Performance**
- The top 10 customers by sales are also among the top 20 customers with the highest order frequency.
- Customers are categorized into high spenders, average spenders, and low spenders.
- A cluster of customers with low frequency but high monetary value constitutes a significant percentage of the customer base.
- There is one high spender with both high frequency and high monetary value.
- Average spenders exhibit high frequency and moderate monetary value.

### Recommendations

**Sales Performance**

-Focus on Central Region Sales: Continue to capitalize on the strong sales in the central region, especially for technology products. Consider introducing promotions or new product launches to further boost sales in this area.
-Boost First Quarter Sales: Implement targeted marketing campaigns and promotions during the first quarter to mitigate the traditionally low turnover period and increase sales.
-Leverage Fourth Quarter Peak: Maximize the high sales potential in the fourth quarter by planning ahead with adequate inventory, staffing, and marketing strategies to meet increased demand.


**Product Performance**

-Enhance Product Returns Revenue: Investigate the factors driving high returns in technology products and find ways to optimize revenue from these returns.
-Optimize Inventory Management: Continuously monitor order quantities and adjust inventory levels to match demand, ensuring optimal stock levels for office supplies, technology, and furniture categories.
-Improve Customer Education: Educate customers on the proper use and benefits of technology products to reduce returns and enhance customer satisfaction.


**Shipping Performance**

-Reduce Delivery Truck Freight Costs: Explore alternative shipping options or negotiate better rates with delivery truck providers to reduce freight costs. Consider optimizing the packaging of jumbo boxes and drums to minimize costs.
-Analyze Express Air Costs: Conduct a detailed analysis to identify the factors contributing to the high freight costs of express air shipments and implement measures to reduce these costs without compromising service quality.
-Enhance Regular Air Efficiency: Maintain and potentially expand the use of regular air shipments, which handle the highest volume of goods and have the lowest average freight cost.


**Customer Performance**

-Engage Low-Frequency High-Value Customers: Develop targeted marketing and engagement strategies to encourage repeat purchases from customers with low frequency but high monetary value.
-Nurture High Spenders: Continue to provide excellent service and personalized offers to maintain and strengthen relationships with high spenders.
-Encourage Average Spenders: Implement loyalty programs or special incentives to convert average spenders into high-frequency, high-value customers.

### limitations

- I had to remove all zero values, which may have resulted in the loss of some important data points.
- Limited historical data available, which may affect the ability to identify long-term trends.
- Potential inaccuracies in the data due to manual entry errors or incomplete records.
- The analysis may not account for all external factors impacting sales, such as economic conditions or market trends.
- The dataset may lack certain demographic information that could provide deeper insights into customer behavior.
- The results are based on the available data and may not be fully representative of the entire business performance.
- The analysis is constrained by the predefined categories and metrics within the dataset.

### References

