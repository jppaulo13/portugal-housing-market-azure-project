# portugal-housing-market-azure-project

I created a data pipeline to acquire housing market data from Kaggle. The data was in CSV format and contained information about housing prices, square footage, number of bedrooms, and other property features in Portugal in 2021.

The pipeline used Azure Data Factory to load the data into a Data Lake Storage Gen2 account. The data was then transformed using Apache Spark on Databricks. The transformation steps included:
 - Cleaning the data to remove any errors or inconsistencies.
 - Enriching the data by adding additional information, such as the region where the property is located and the price per square foot.

The transformed data was then stored in Data Lake Storage Gen2 as transformed data and it was analyzed and explored using SQL on Azure Synapse Analytics. Finally, a dashboard was built using Power BI. The dashboard tracked trends in the Portuguese housing market, such as the average housing price and the number of properties per region.


![Pipeline (1)](https://github.com/jppaulo13/portugal-housing-market-azure-project/assets/101720868/d62841f4-b073-4d00-bb77-a29aedfa6c25)
