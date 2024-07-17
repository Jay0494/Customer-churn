# Customer-churn Project
**Project Introduction: Customer Churn Risk Identification**
This project was initiated by the Freebies WhatsApp Group with the objective of identifying customers at risk of churning. Recognizing the importance of customer retention for sustained business growth, our team focused on leveraging data to proactively address potential churn.
We utilized the Chinook Database as our primary data source. The data extraction process involved obtaining relevant customer, transaction, and behavioral information. Post-extraction, we meticulously cleaned and prepared the data using Python, ensuring its suitability for further analysis.
Through this project, we aim to provide actionable insights and strategies to mitigate customer churn, thereby enhancing customer satisfaction and loyalty.
### Business Question 
Identify customers at risk of churning based on their purchase history and suggest targeted promotions to retain them
## Tools
- Python
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
   - After the data was successfully cleaned and transformed, it was exported to a CSV file format. This format was chosen for its compatibility and ease of use with various data analysis tools.

4. **Loading Data into Power BI**:
   - The cleaned CSV file was then imported into Power BI Desktop. Power BI's robust visualization and analytical capabilities were leveraged to conduct a detailed analysis and derive actionable insights.

