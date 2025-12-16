# End-to-End Modern Data Stack Pipeline  
**DBT | Snowflake | Airflow | AWS**

## Project Overview
This project demonstrates an end-to-end ETL pipeline built using DBT, Snowflake, Apache Airflow, and AWS. The pipeline ingests CSV data from Amazon S3, loads it into Snowflake, transforms and models the data using DBT, and orchestrates the workflow using Airflow with automated scheduling and monitoring.

## Business Impact
Enabled reliable, scalable analytics by automating end-to-end data pipelines, improving data quality, reducing manual effort, and accelerating insight delivery for business stakeholders.

## Tech Stack
- **Languages:** Python, SQL  
- **Data Warehouse:** Snowflake  
- **Transformation:** DBT  
- **Orchestration:** Apache Airflow  
- **Cloud Services:** AWS EC2, Amazon S3, AWS SNS  
- **Visualization:** AWS QuickSight  

## Data Flow
1. CSV files are uploaded to **Amazon S3**
2. Python scripts load data from S3 into **Snowflake**
3. **DBT** models transform and aggregate the data
4. **Airflow DAGs** orchestrate and schedule the pipeline
5. Alerts are triggered via **AWS SNS** on failures
6. Final data is visualized in **AWS QuickSight**

## Features
- Automated ETL pipeline
- Modular DBT models with testing and documentation
- Airflow scheduling and dependency management
- Error handling and failure notifications
- Cloud-native and scalable architecture

## Use Case
The project uses Netflix datasets to answer business-driven questions and generate analytical insights through structured data modeling.

## How to Run (High Level)
1. Set up AWS EC2 with Airflow, DBT, and Snowflake
2. Upload source CSV files to Amazon S3
3. Configure Snowflake credentials and DBT profiles
4. Trigger the Airflow DAG to execute the pipeline

## Future Enhancements
- Incremental DBT models
- CI/CD for DBT deployments
- Advanced data quality checks
- Additional dashboards and KPIs
