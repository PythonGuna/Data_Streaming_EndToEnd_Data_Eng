Introduction:

This end-to-end data streaming project fetches data from a Random User API using Apache Airflow and sends it to Kafka. It incorporates Schema Registry and Control Center to manage and visualize the messages, with ZooKeeper handling Kafka's coordination. The entire setup runs in Docker containers for easy deployment and management. The data is streamed from Kafka using a PySpark master-worker architecture, processed, and stored in Cassandra.
Flow Diagram:

![workflow](https://github.com/user-attachments/assets/44170081-b7ee-496f-8ad4-a25271c6d9c7)

TechStack:

  Apache Airflow
  
  Python
  
  Apache Kafka
  
  Apache Zookeeper
  
  Apache Spark
  
  Cassandra
  
  PostgreSQL
  
  Docker
  






