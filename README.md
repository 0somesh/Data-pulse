# Data Pulse - Streaming With TCP Socket, Apache Spark, OpenAI LLM, Kafka and Elasticsearch 

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [What You'll Learn](#what-youll-learn)
- [Technologies](#technologies)
- [Getting Started](#getting-started)


## Introduction

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline using TCP/IP Socket, Apache Spark, OpenAI LLM, Kafka and Elasticsearch. It covers each stage from data acquisition, processing, sentiment analysis with ChatGPT, production to kafka topic and connection to elasticsearch.

The project is designed with the following components:

- **Data Source**: We use `yelp.com` dataset for our pipeline.
- **TCP/IP Socket**: Used to stream data over the network in chunks
- **Apache Spark**: For data processing with its master and worker nodes.
- **Confluent Kafka**: Our cluster on the cloud
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Kafka Connect**: For connecting to elasticsearch
- **Elasticsearch**: For indexing and querying

## What You'll Learn

- Setting up data pipeline with TCP/IP.
- Real-time data streaming with Apache Kafka
- Data processing techniques with Apache Spark
- Realtime sentiment analysis with OpenAI ChatGPT
- Synchronising data from kafka to elasticsearch
- Indexing and Querying data on elasticsearch

## Technologies

- Python3
- TCP/IP
- Confluent Kafka
- Apache Spark
- Docker
- Elasticsearch

## Getting Started

1. Clone the repository:
   
    git clone

2. Navigate to the project directory:
   
..............
3. Run Docker Compose to spin up the spark cluster:
   .............
    

