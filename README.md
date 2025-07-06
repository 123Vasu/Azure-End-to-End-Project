## Azure End To End Project
# Azure End-to-End Data Pipeline Project

This project demonstrates an end-to-end data pipeline architecture using various Azure services including **Data Factory**, **Data Lake Gen2**, **Databricks**, **Synapse Analytics**, and **Power BI**.

---

## 🔧 Architecture Overview

The following diagram illustrates the high-level architecture of the pipeline:

![Azure Data Pipeline Architecture](https://github.com/123Vasu/Azure-End-to-End-Project/blob/main/Azure%20End%20to%20End%20Project.drawio.png?raw=true)

---

## 📌 Components Used

- **HTTP Source**: Simulated or real-time data from external APIs.
- **Azure Data Factory**: For data ingestion.
- **Azure Data Lake Gen2**: Raw and transformed data storage.
- **Azure Databricks**: Data cleaning, transformation, and enrichment.
- **Azure Synapse Analytics**: Data serving and querying.
- **Power BI**: Final reporting and visualization layer.

---

## 🚀 Pipeline Flow

1. **Data Ingestion**: Data Factory pulls data from an HTTP endpoint.
2. **Raw Storage**: Data is stored in Azure Data Lake Gen2.
3. **Transformations**: Databricks notebooks process and clean the raw data.
4. **Serving Layer**: Transformed data is stored and queried via Synapse.
5. **Reporting**: Power BI connects to Synapse for real-time dashboards.

## 📊 Sample Data

This project uses sample CSV data files for demonstration and testing purposes. These files represent the raw data ingested through the pipeline.

### 🔹 Data Files

The following CSV files are included in the `/data` folder:

- `AdventureWorks_Calendar.csv`
- `AdventureWorks_Customers.csv`
- `AdventureWorks_Product_Categories.csv`
- `AdventureWorks_Product_Subcategories.csv`
- `AdventureWorks_Products.csv`
- `AdventureWorks_Returns.csv`
- `AdventureWorks_Sales_2015.csv`
- `AdventureWorks_Sales_2016.csv`
- `AdventureWorks_Sales_2017.csv`
- `AdventureWorks_Territories.csv`

