# Snowflake Data Pipeline with AWS Glue and Airflow

## Overview
This project demonstrates an **ETL pipeline** that:
1. **Extracts** data from AWS S3.
2. **Transforms** it using AWS Glue.
3. **Loads** it into Snowflake.
4. **Orchestrates** the pipeline using Apache Airflow.

## Architecture
![Pipeline Diagram](assets/architecture.png)

## Setup Instructions
1. Deploy an AWS S3 bucket and upload sample CSV data.
2. Configure AWS Glue with an ETL job to clean and process data.
3. Set up Apache Airflow and add the DAG (`snowflake_pipeline.py`).
4. Run the Airflow DAG to complete the ETL process.

## Technologies Used
- **Snowflake** (Data Warehousing)
- **AWS Glue** (ETL Processing)
- **AWS S3** (Data Storage)
- **Apache Airflow** (Orchestration)
- **DBT** (Data Transformation)
- **Python** (Scripting)
