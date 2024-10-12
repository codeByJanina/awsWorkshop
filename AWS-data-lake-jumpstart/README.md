# AWS Data Lake Pipeline - Mimmit Koodaa Jumpstart Workshop

In this workshop, I built an end-to-end serverless data pipeline using AWS services as part of the *Mimmit Koodaa - Data Lake Jumpstart* workshop.

## Project Overview

This project demonstrates how to use various AWS services to create a scalable, serverless data lake architecture.

## AWS Services Used:

- **Amazon S3:** Central storage for raw and processed data.
- **AWS Glue:** Managed ETL service for data transformation and metadata management.
- **Amazon Athena:** Serverless query service for analyzing data with SQL.
- **Amazon QuickSight:** Business intelligence service for data visualization.

## Lab Overview

- **Lab 1 – Discovering and Cataloging Your Data:** Created an AWS Glue Crawler to auto-discover the schema of data stored in Amazon S3. The discovered information was registered in the AWS Glue Data Catalog.
- **Lab 2 – Exploring Your Data** In this lab, I used Amazon Athena to explore data stored in Amazon S3 and identified data quality issues. I also updated table properties in the AWS Glue Data Catalog to handle CSV files with quoted values properly.
- **Lab 3 – Transforming Your Data** I used AWS Glue Studio to visually create a data transformation job. The goal was to clean and enrich the raw_yellow_tripdata by joining it with location data and saving the transformed dataset to Amazon S3 in an optimized format.
- **Lab 4 – Enriching Your Data** I used data visualization and enrichment techniques to gain better insights into the NYC taxi data. I created a Glue Crawler to catalog the transformed data, validated it in Amazon Athena, and enriched it with additional contextual information such as vendor details, rate types, and payment methods.
- **Lab 5 – Visualizing Your Data**  I connected Amazon QuickSight to the enriched taxi trip data stored in S3 and used it to create a visual representation of the flow of yellow taxi trips from pickup boroughs to drop-off boroughs. This enabled deeper insights into taxi traffic patterns.


