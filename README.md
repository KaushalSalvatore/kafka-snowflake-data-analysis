#### kafka-snowflake-data-analysis

**end-to-end real-time data engineering project using Apache Kafka, Python, and Snowflake.**

- This project demonstrates how Kafka is actually used in real systems — including message keys, partitioning, streaming data validation, offset management, and warehouse-first analytics — not just basic producers and consumers.

- We follow a Medallion Architecture (Bronze → Silver → Gold) approach, where:
Kafka handles real-time ingestion and data quality
Python handles stream processing
Snowflake handles analytics and business logic using SQL


