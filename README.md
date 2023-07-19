# ETL-pipeline---Azure

Developed and deployed an end-to-end ETL (Extract, Transform, Load) pipeline using Azure Data factory, Databricks, Data Lake, Azure SQL and PySpark programming. 

Extracted data of a company’s Employees dataset from different sources, such as - .csv, .json, .xml etc. formats and gathered all of them into Azure blob storage, a source container. Created cluster on Azure Databricks and accessed all those data inside Databricks notebooks. Applied necessary transformation and data cleaning, such as – identifying and handling missing/null values, removing duplicates, correcting inconsistent data, handling outliers and erroneous data, standardizing data, handling data integrity issues etc. using Scala, PySpark, Python etc. Then, stored the transformed data into centralized locations – Azure SQL database and Azure Databricks Delta Lake DBFS.

Next, applied SQL queries to retrieve necessary information and generated various data analysis-based dashboards to visualize the following:

•	Top five expensive results in each department and plot them on line graph, 

•	Show cost on world map

•	Plot the graph by total salary per country and give a percentage break up 

•	Cost of each department per country, and 

•	Find out average maximum in salary in each department.


![image](https://github.com/Jenia-Jeba/ETL-pipeline---Azure/assets/39514905/89373946-e41f-4c21-98f6-5d69f59e5846)


And after that, moved all these processed files to a destination container in Azure blob storage. Orchestrated all these processes through creating pipeline in Azure Data Factory.


![image](https://github.com/Jenia-Jeba/ETL-pipeline---Azure/assets/39514905/c0e804ac-c6c5-4017-ad7e-c6ee02031af7)



