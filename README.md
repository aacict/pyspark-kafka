# PySpark Kafka Integration
Note: We don't need zookeeper from the introduction of kafka kRaft.

This repository demonstrates how to integrate Apache Spark (PySpark) with Apache Kafka for real-time data streaming and processing.

## Project Description

This project provides a basic example of how to:

* **Consume data from Kafka using PySpark:** Read data from a Kafka topic into a Spark DataFrame for processing.
* **Produce data from app using PySpark:** Send data to a Kafka top using pyspark.

This repository serves as a starting point for building more complex real-time data pipelines using PySpark and Kafka.

## Prerequisites

Before running this project, ensure you have the following installed:

* Apache Spark
* Apache Kafka
* Python 3.x
* PySpark library

## Installation

1.  **Clone the repository:**

    ```bash
    git clone ..
    cd pyspark-kafka
    ```

2.  **Install the required dependencies.:**

3.  **Ensure Kafka and Spark are running:**

    * Start your Kafka server.
    * Start your Spark session.

## Usage

1.  **Configure Kafka connection:**

    * Modify the Kafka broker address and topic name in the PySpark script.

2.  **Run the PySpark script from specific section in the notebook :**

3.  **Produce messages to Kafka:**

    * Use a Kafka producer to send messages to the configured topic.

4.  *Consume messages from PySpark:**

    * The PySpark script will process the incoming messages and display the results.
