# Customer-churn Project
**Project Introduction: Customer Churn Risk Identification**
This project was initiated by the Freebies WhatsApp Group with the objective of identifying customers at risk of churning. Recognizing the importance of customer retention for sustained business growth, our team focused on leveraging data to proactively address potential churn.

*Chinooks* is a prominent player in the music streaming industry, dedicated to delivering an exceptional user experience. However, recent data indicates a significant customer churn rate, prompting an in-depth analysis to identify underlying issues and develop effective strategies to improve customer retention. This report delves into customer churn data, examining trends and insights to provide actionable recommendations for Chinooks' growth and stability.

We utilized the Chinooks Database as our primary data source. The data extraction process involved obtaining relevant customer, transaction, and behavioral information. Post-extraction, we meticulously cleaned and prepared the data using Python, ensuring its suitability for further analysis.
Through this project, we aim to provide actionable insights and strategies to mitigate customer churn, thereby enhancing customer satisfaction and loyalty.

![chinooks ](https://github.com/user-attachments/assets/009af36d-a18a-4bfa-8b84-48c9c853551d)

### Project Objective 
The primary objective of this project is to analyze customer churn data to uncover key insights and patterns that contribute to customer attrition. By understanding these factors, we aim to provide strategic recommendations that will help Chinooks enhance customer retention, optimize marketing efforts, and ultimately increase revenue.

## Tools
- Python
- Power query
- Dax
- PowerBi

### Data Processing for Business Analysis

To address the business question at hand, I accessed the Chinook database to retrieve the relevant customer and invoice datasets. This process involved several key steps to ensure the data was suitable for analysis.

#### Data Preparation Workflow

1. **Library Imports and Data Loading**: 
   - I imported the necessary libraries in Python, including pandas for data manipulation.
   - The customer and invoice datasets were loaded from the Chinook database into Python data frames.

2. **Data Cleaning and Transformation**:
   - **Removed Unwanted Columns**: I identified and removed columns that were not relevant to the analysis to streamline the dataset and improve processing efficiency.
   - **Formatted Data Types**: Data types were formatted appropriately to ensure consistency and accuracy. For example, date field was converted to datetime object.
   - **Renamed Columns**: Columns were renamed to more descriptive and user-friendly names to facilitate easier understanding and analysis.

3. **Exporting Cleaned Data**:
   - After the data was successfully cleaned and transformed, it was exported as a CSV file format. This format was chosen for its compatibility and ease of use with various data analysis tools.

4. **Loading Data into Power BI**:
   - The cleaned CSV files where then imported into Power BI Desktop. Power BI's robust visualization and analytical capabilities were leveraged to conduct a detailed analysis and derive actionable insights.
   - In powerbi I merged the First and last name to cust_name, created a calender table and other calculated measures for analytical purposes.

## Analysis and Insights

#### Customer Data Overview (2013)
- **Lost Customers**: 29
- **Active Customers**: 46
- **Churn Rate**: 49.2%

#### Top 10 Countries by Revenue
- **USA**: $85.14
- **Canada**: $72.27
- **France**: $40.59
- **Brazil**: $37.62
- **Czech Republic**: $36.75
- **United Kingdom**: $28.71
- **Argentina**: $24.75
- **Portugal**: $24.75
- **Finland**: $15.84
- **Netherlands**: $15.84

#### Top 10 Countries by Customers
- **USA**: 11 active customers
- **Canada**: 7 active customers
- **Brazil**: 4 active customers
- **France**: 4 active customers
- **United Kingdom**: 3 active customers
- **Czech Republic**: 2 active customers
- **Argentina**: 1 active customer
- **Finland**: 1 active customer
- **Netherlands**: 1 active customer
- **Portugal**: 1 active customer

### Insights
1. **High Churn Rate**: With a churn rate of 49.2%, nearly half of the customers leave the service, indicating a critical need for retention strategies.
2. **Revenue vs. Customer Base**: The USA and Canada lead in revenue and customer base, suggesting a strong market presence. However, other countries like France and Brazil, while contributing significantly to revenue, have a smaller customer base, highlighting potential growth opportunities.
3. **Low Customer Concentration**: Countries like Finland, Netherlands, and Portugal have minimal active customers despite their contribution to revenue, indicating untapped market potential.

### Recommendations

1. **Enhance Customer Engagement**: Develop personalized marketing campaigns and loyalty programs tailored to the preferences of users in high churn regions.
2. **Improve Service Quality**: Invest in customer support and enhance the user interface to improve overall customer satisfaction and reduce churn.
3. **Market Expansion**: Focus on increasing the customer base in high-revenue but low-customer countries like France and Brazil through targeted promotions and localized content.
4. **Data-Driven Strategies**: Utilize advanced analytics to monitor customer behavior, predict churn, and implement proactive measures to retain at-risk customers.
5. **Feedback Mechanisms**: Establish robust feedback systems to gather customer insights regularly, allowing for continuous improvement in service offerings.

### Next Steps

1. **Conduct Surveys**: Implement customer satisfaction surveys to gather direct feedback on service pain points.
2. **Develop Retention Programs**: Create and test pilot retention programs in high-churn regions, analyzing effectiveness before a broader rollout.
3. **Enhance Analytics Capabilities**: Invest in advanced analytics tools to better understand customer behavior and predict future churn trends.
4. **Optimize Marketing Efforts**: Refine marketing strategies based on insights from churn data, focusing on personalization and customer value propositions.

### Summary

Chinooks faces a significant challenge with a 49.2% churn rate, emphasizing the need for strategic interventions to retain customers. By analyzing customer data, we identified key trends and insights, particularly in high-revenue regions with low customer bases. Implementing targeted engagement strategies, improving service quality, and expanding market reach are critical steps. Through continuous data-driven analysis and proactive customer retention measures, Chinooks can enhance customer loyalty, reduce churn, and drive long-term growth.

  
     



