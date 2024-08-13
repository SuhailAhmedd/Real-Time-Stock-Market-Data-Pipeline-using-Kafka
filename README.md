# Stock Market Real-Time Data Engineering Project

This repository showcases an end-to-end data engineering project focused on real-time stock market data analysis using Apache Kafka, AWS services, and Python.

## Architecture

![Architecture](Architecture.jpg)

## Technology Used

### Programming Language:
- **Python:** For scripting and automating various parts of the data pipeline.

### Amazon Web Services (AWS):
- **S3:** Simple Storage Service for storing raw and processed data.
- **Athena:** Querying the processed data.
- **Glue Crawler:** Creating and updating the data catalog.
- **Glue Catalog:** Maintaining metadata about the data stored in S3.
- **EC2:** Running Kafka and other processing jobs.

### Apache Kafka:
- Real-time data streaming and processing.

  ![Apache Kafka logo](Apache_kafka.png)
  
### Apache Kafka Workflow Engine:
  ![Apache Kafka Workflow Engine](kafka_work_flow_Engine.png)

## Dataset Used

You can use any stock market dataset as the primary focus is on the operation side of data engineering (building the data pipeline).

- The dataset used in this project: [Stock Market Data](https://github.com/SuhailAhmedd/Real-Time-Stock-Market-Data-Pipeline-using-Kafka/blob/main/indexProcessed.csv)

## Project Description

This project involves setting up a real-time data pipeline for stock market data using Apache Kafka, AWS services, and Python. The pipeline collects, processes, and stores data for efficient querying and analysis.

## Use Cases

- **Real-Time Data Collection:** Using Kafka to stream stock market data in real-time.
- **Data Processing:** Utilizing Python scripts to process the incoming data.
- **Data Storage:** Storing raw and processed data in AWS S3.
- **Data Cataloging:** Using Glue Crawler and Glue Catalog to manage metadata.
- **Data Querying:** Querying processed data using AWS Athena.

## Detailed Steps

1. **Real-Time Data Collection with Kafka**
    - Set up a Kafka cluster on AWS EC2.
    - Create Kafka topics for stock market data.
    - Produce data to Kafka topics using Python.

2. **Data Processing with Python**
    - Consume data from Kafka topics using Python scripts.
    - Process and transform the data.
    - Store processed data in AWS S3.

3. **Data Storage in AWS S3**
    - Create S3 buckets for raw and processed data.
    - Store incoming raw data and processed data in respective buckets.

4. **Data Cataloging with AWS Glue**
    - Use Glue Crawler to scan S3 buckets and create/update the data catalog.
    - Manage metadata using Glue Catalog.

5. **Data Querying with AWS Athena**
    - Configure Athena to query processed data in S3.
    - Use SQL queries for data analysis and insights.

## Conclusion

This project provides a comprehensive approach to handling Real-Time Stock Market Data using a combination of Apache Kafka, AWS services, Python, and SQL.

