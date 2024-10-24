ETL Pipeline using dbt, snowflake and airflow
========

Overview
========

This project demonstrates the creation of an ETL (Extract, Transform, Load) pipeline using dbt (data build tool), Snowflake as the data warehouse, and Apache Airflow for orchestration. The pipeline extracts and transforms the TPCH SF1 sample data into a structured data warehouse environment, utilizing dbt for modeling and testing.

Project Contents
================

In this project, I set up a Snowflake data warehouse where I created a dedicated database and user role. Using dbt, I implemented transformations on the TPCH SF1 sample data, allowing for efficient data modeling. I also developed macros and tests to ensure the integrity and accuracy of the data. Finally, I orchestrated the entire data pipeline using Astronomer Cosmos, leveraging Airflow to schedule and manage the data workflows.

Tools
===========================

- Snowflake: Cloud-based data warehouse solution.
- dbt: Data transformation tool for analytics.
- Apache Airflow: Workflow orchestration tool for scheduling and managing data pipelines.
- Astronomer Cosmos: Platform for managing Airflow deployments.

Project Flow
=================================

1. Setup Snowflake:
    - Created a data warehouse, database, and user role in Snowflake.

2. Extract Data:
    - Utilized the TPCH SF1 sample data available in Snowflake.

3. Transform Data:
    - Used dbt to define models for transforming the raw data into structured formats.
    - Wrote custom macros to facilitate complex transformations.
    - Implemented tests to ensure data quality and correctness.

4. Load Data:
    - Loaded the transformed data into the created data warehouse in Snowflake.

5. Schedule Pipeline:    
    - Configured Airflow using Astronomer Cosmos to schedule the execution of dbt models and manage the ETL workflow.

Prerequisites
=======

- Access to Snowflake account.
- dbt installed and configured.
- Airflow setup with Astronomer Cosmos.

