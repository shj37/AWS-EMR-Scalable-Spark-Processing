# AWS EMR for Scalable Spark Processing: A Comprehensive Guide

![project overview](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*gB2wBx2TsVtN6E7ura-iHg.jpeg)

## Overview

This repo shows how to use **AWS EMR** and **Apache Spark** to process big data in the cloud. It includes scripts and notes from my Medium guide on setting up and running Spark jobs.

## Features

- Cluster Setup: Configured EMR with IAM, VPCs, and S3.
- Spark Jobs: PySpark scripts for interactive (**EMR Studio**) and automated (**EMR Steps**) processing.

## Tech Stack
- AWS EMR, S3, IAM, VPC
- Apache Spark (PySpark)
- Python, Jupyter Notebook

## Getting Started

1. Set up AWS with IAM roles, VPCs, and an S3 bucket (see Medium guide).
2. Launch an EMR cluster with Spark installed.
3. Run `spark-etl.py` via EMR Steps or explore notebooks in EMR Studio.
4. Check results in your S3 bucket.

## Full Guide

[Medium article series](https://medium.com/@jushijun/building-a-banking-customer-data-warehouse-an-end-to-end-guide-using-aws-and-dbt-c058ebe7af35)

## References

- @CodeWithYu https://www.youtube.com/watch?v=ZFns7fvBCH4&t=712s&ab_channel=CodeWithYu
  - https://github.com/airscholar/EMR-for-data-engineers
- @tuplespectra https://www.youtube.com/watch?v=PeaLln90YXg&ab_channel=tuplespectra