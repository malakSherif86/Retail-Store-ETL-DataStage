# Retail-Store-ETL-DataStage
# Project Overview:
This project centers on leveraging IBM InfoSphere DataStage to craft efficient ETL (Extract, Transform, Load) pipelines. These pipelines are tailored to establish data marts and streamline the analysis of data sourced from a hypothetical retail store. The primary aim is to ensure the preservation of all dimension changes throughout the ETL process.
# Data Source:
![image](https://github.com/malakSherif86/Retail-Store-ETL-DataStage/assets/156374396/ae24abdf-3278-4a85-ada2-3cbcb9e0b264)

# Project Steps:

Extraction: Acquiring retail, customer, and product data from the data warehouse.

Transformation: Enhancing the extracted data by converting customer names to uppercase.

Loading: Depositing the transformed data into a Retail Data Mart.

Analysis: Fulfilling various business needs through the Retail Data Mart, such as:

Displaying the count of all transactions for each employee at each store.
Identifying the customer type that yields the highest profit. For instance, showcasing that "foreign" customer types make 5 transactions while "citizen" customer types make 3 transactions, resulting in the maximum profit by foreign customers. This DataMart is labeled "ACTIVATIONSALES_DATA_MART."
Awarding bonus equations to customers based on their profit contributions, where Bonus Equation = Annual_Income (in k$) * SpendingScore * 100.
# Project Files:

DataStage Jobs: Contains the dsx jobs utilized.
Dataset: The dataset employed in constructing the star schema model.
Output Files: Output generated from each job.
Screenshots: Visual documentation of each job.
