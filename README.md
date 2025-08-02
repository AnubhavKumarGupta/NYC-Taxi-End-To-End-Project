# NYC-Taxi-End-To-End-Project

- A complete end-to-end data engineering project that replicates a real-world data pipeline using the NYC Taxi dataset.
- Built using Azure Data Factory, Azure Data Lake Gen2, Databricks, and Delta Lake, following the Medallion Architecture (Bronze, Silver, Gold).

---
## 📌 Key Features
- 🔄 Real-time data ingestion from a public NYC Taxi API using Azure Data Factory
- 🗂️ Clean separation of data into Bronze, Silver, and Gold layers using Medallion Architecture
- ⚙️ Parameterized and dynamic pipelines using ForEach, expressions, and variables
- 🧹 Data transformation using PySpark in Databricks notebooks with schema enforcement
- 🪙 Stored cleaned data in Delta Lake format for efficient querying, updates, deletes, and time travel
- 🧪 Created managed and external Delta tables for analytics-ready data
- 📊 Final Gold layer is connected to Power BI for reporting and visualization

---
## 💻 Technologies Used
- **Azure Data Factory (ADF):** For orchestrating data workflows and API ingestion
- **Azure Data Lake Storage Gen2:** For storing data in a scalable file-based lakehouse format
- **Azure Databricks:** For performing data transformation using PySpark
- **Delta Lake:** For optimized storage with ACID compliance and version control
- **PySpark:** To write transformation logic on large-scale datasets
- **Power BI:** For optional dashboarding and visual analytics
- **REST API:** As a source system to simulate real-time data flow
- **GitHub:** For source control and documentation




--- 

# 🏗️ Architecture
- Data ingestion from a public API using Azure Data Factory (ADF)
- Storing raw, cleaned, and aggregated data in Azure Data Lake Gen2 (Bronze → Silver → Gold)
- Data transformation using PySpark in Azure Databricks
- Storing transformed data in Delta Lake format with time travel and versioning
- Serving the final Gold layer data to Power BI for visualization
<img width="1564" height="1116" alt="NYC TAXI Architecture" src="https://github.com/user-attachments/assets/a10c52c2-6997-4125-b60a-5dc55d19fa21" />

---

# 📦 Resource Group
This shows the Azure Resource Group that contains all the required services for this project, such as:
- Azure Data Factory
- Azure Storage Account (Data Lake Gen2)
- Azure Databricks 

Each resource is logically grouped for better organization and management.

<img width="1920" height="816" alt="image" src="https://github.com/user-attachments/assets/5a816998-6d37-44ba-bec7-d33d2c89bea2" />


# Medeallion Architecture 
This shows the container structure inside Azure Data Lake Gen2. It includes:

- **bronze** → Raw API and source data files
- **silver** → Cleaned and structured data after transformation
- **gold** → Final aggregated data ready for analytics and reporting

This structure follows the Medallion Architecture pattern.

<img width="1920" height="856" alt="image" src="https://github.com/user-attachments/assets/67ccffd4-02fb-4e4c-99d9-d32df0a2d92f" />

## Bronze Layer

<img width="1918" height="720" alt="image" src="https://github.com/user-attachments/assets/1bf85232-852d-4b50-9958-cf498809c5c9" />

##

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/edb2efb1-addd-4313-b8e8-11a375efc47f" />



##

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7855f7e0-b12a-473b-897d-a98b9f7a4e5e" />
