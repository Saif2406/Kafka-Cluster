# Kafka-Cluster
Apache Kafka Cluster (3 Brokers) setup on Ubuntu Server

![image](https://github.com/Saif2406/Kafka-Cluster/assets/55284450/e6d07c0c-4efe-4a84-acfb-1cdc84a851ca)

Understanding Kafka Cluster Architecture

the understanding of Kafka’s cluster architecture. At its core, a Kafka cluster comprises Brokers, Topics, Partitions, and Replication.

**Brokers:**
Brokers are essentially the Kafka servers responsible for handling the message storage, retrieval, and replication. Think of them as the workhorses of the Kafka ecosystem. Each broker maintains one or more partitions for each topic it hosts. These partitions are distributed across brokers for load balancing and fault tolerance.

