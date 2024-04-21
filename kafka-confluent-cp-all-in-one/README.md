# Kafka Confluent Docker 

This Docker image is based on the Kafka Confluent [cp-all-in-one](https://github.com/confluentinc/cp-all-in-one/tree/7.5.0-post/cp-all-in-one) which is a Confluent Enterprise License version of Confluent Platform, including Confluent Server (and ZooKeeper), Schema Registry, a Kafka Connect worker with the Datagen Source connector plugin installed, Confluent Control Center, REST Proxy, and ksqlDB.

## How to run?

1. Clone the project.
2. Run docker-compose.
    ```
    cd kafka-confluent-cp-all-in-one/docker
    docker-compose up -d
    ```
3. Access the Confluent Control Center to check the cluster healthy and its properties -> http://localhost:9021/

## Quick start

Follow the page to buid a basic streaming app on mock data: https://docs.confluent.io/platform/current/platform-quickstart.html#step-2-create-ak-topics-for-storing-your-data 

Another quick start document: https://developer.confluent.io/quickstart/kafka-on-confluent-cloud/