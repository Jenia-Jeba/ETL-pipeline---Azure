# End-to-End ETL Pipeline Using Azure Technologies

This project showcases the development and deployment of a comprehensive ETL (Extract, Transform, Load) pipeline leveraging various Azure technologies. The pipeline efficiently processes a company's Employees dataset sourced from multiple formats like .csv, .json, and .xml files. The entire workflow is orchestrated using Azure Data Factory, integrating Azure Blob Storage, Azure Databricks, Data Lake, Azure SQL, and PySpark programming.


![image](https://github.com/Jenia-Jeba/ETL-pipeline---Azure/assets/39514905/89373946-e41f-4c21-98f6-5d69f59e5846)


## Key Steps and Features:

#### Data Extraction: 
The pipeline extracts data from diverse sources, such as .csv, .json, and .xml files, and consolidates them into an Azure Blob Storage container, serving as the initial data source.

#### Azure Databricks Integration: 
A Databricks cluster is created to process the extracted data. Using Scala, PySpark, and Python, we perform vital transformations and data cleaning operations, including handling missing/null values, removing duplicates, correcting inconsistencies, and handling outliers and erroneous data.

#### Data Standardization: 
The pipeline ensures data consistency by standardizing data across different formats and scales. This step converts dates into a specific format, normalizes numerical variables, and transforms categorical variables into a standardized representation.

#### Centralized Data Storage: 
The transformed data is stored in two central locations for efficient access and analysis. The processed data is saved in an Azure SQL database and an Azure Databricks Delta Lake DBFS.

#### Data Analysis and Visualization: 
SQL queries are applied to retrieve essential information, enabling the creation of data analysis-based dashboards. These dashboards visualize various insights, such as the top five expensive results in each department displayed on a line graph, a world map showcasing cost distribution, total salary per country with a percentage breakdown using pie charts, and bar graphs illustrating average, minimum, and maximum salary in each department.

#### Moving Processed Files: 
All the processed data files are moved to a destination container in Azure Blob Storage, maintaining a well-organized data storage system.

#### Pipeline Orchestration: 
The entire ETL workflow is orchestrated through the creation of a seamless pipeline using Azure Data Factory. This ensures the smooth and efficient execution of the data processing steps.

### Project Benefits:

Centralized and unified data storage for easy accessibility and analysis.
Advanced data cleaning and transformation for improved data quality.
Interactive data analysis dashboards for better insights and decision-making.
Automated and orchestrated ETL pipeline for efficient and reliable data processing.
Technologies Used:

- Azure Data Factory
- Azure Blob Storage
- Azure Databricks
- Data Lake
- Azure SQL
- PySpark, Scala, Python


This project exemplifies the power of Azure technologies in building robust, scalable, and sophisticated ETL pipelines, enabling organizations to efficiently process and analyze large and diverse datasets for informed decision-making.


![Capture](https://github.com/Jenia-Jeba/ETL-pipeline---Azure/assets/39514905/40dc61e2-b7e6-4bcd-a923-09f389f75f16)






