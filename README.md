# Apache Spark Data Pipeline for Education Census

## Overview
This project utilizes **Apache Spark** to process and analyze the Brazilian National Basic Education Census data from 2010 to 2020. The goal is to transform raw data into a **Star Schema** format for optimized querying and analysis.

## Technologies Used
- **Apache Spark** (PySpark)
- **PostgreSQL**
- **Docker** & **Docker Compose**
- **Python 3.6+**
- **Psycopg2** (PostgreSQL connector)
- **Requests** (for downloading files)

## Setup

### Requirements
- Python 3.6+
- Apache Spark installed with PostgreSQL JDBC driver
- Docker and Docker Compose

### Postgres Configuration
Create a PostgreSQL container with the following settings:
- **POSTGRES_USER**: `censo`
- **POSTGRES_PASSWORD**: `123`
- **POSTGRES_DB**: `censo_escolar`

Description
- Developed an ETL pipeline using Apache Spark to process and transform over 2.2GB of data from the Brazilian National Basic Education Census into a Star Schema for optimized querying and analytics.
- Leveraged PySpark to convert raw CSV files into Parquet format, significantly improving query performance and handling large datasets efficiently.
- Implemented the pipeline with PostgreSQL and utilized Docker to create a seamless environment for data storage, integration, and dashboard creation using Metabase for BI reporting.

