# Youtube-Data-Engineering-Project
Developed an end-to-end project, including a data lake using AWS tools, ETL design, Spark, and BI integration.

## Overview
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Project Goals
Data Ingestion — Build a mechanism to ingest data from different sources
ETL System — Getting data in raw format, transforming this data into the proper format
Data lake — Getting data from multiple sources so we need centralized repo to store them
Scalability — As the size of our data increases, we need to make sure our system scales with it
Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
Reporting — Build a dashboard to get answers to the question we asked earlier

## Services
Amazon S3, AWS IAM, QuickSight, AWS Glue, AWS Lambda, AWS Athena

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new
