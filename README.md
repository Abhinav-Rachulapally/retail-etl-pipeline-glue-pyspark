# Retail ETL Pipeline with AWS Glue & PySpark

This project demonstrates an end-to-end ETL pipeline for retail sales data using AWS Glue, S3, PySpark, and Redshift.

## 🧰 Tech Stack
- AWS Glue (ETL orchestration)
- PySpark
- Amazon S3
- Amazon Redshift
- AWS IAM
- Python

## 📁 Folder Structure
retail-etl-pipeline-glue-pyspark/
│
├── scripts/
│   └── retail_glue_job.py
│
├── dashboard/
│   └── sales_dashboard.png   (optional)
│
└── README.md

## 🚀 Pipeline Overview

1. **Data Ingestion**: Raw sales data uploaded to S3 bucket
2. **Transformation**: AWS Glue job runs PySpark to clean & transform data
3. **Loading**: Final data saved to Redshift in Parquet format
4. **Analysis**: Ready for Power BI, Redshift queries, or Athena

## 📊 Reporting

The transformed data from Redshift was analyzed using Power BI dashboards.
Metrics included:

- Daily sales trends
- Top-selling products
- Store-wise performance


## 📊 Sample Use Case

- Dataset: 1M+ sales records across 50 stores
- Replaced Excel-based reporting → reduced latency by ~80%

## 🙋‍♂️ Author
Abhinav Rachulapally  
Data Engineer with 2+ years experience in building data pipelines
