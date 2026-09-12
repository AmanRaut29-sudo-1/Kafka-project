A hands-on Apache Kafka event-driven order processing system built using Docker(docker-compose), Python, Kafka , partitions, and consumer groups.

The project demonstrates how Kafka can be used to build scalable, fault-tolerant, asynchronous, and event-driven applications.

Project Objectives :- 

The main objectives of this project are to understand and implement:

Apache Kafka
Kafka brokers
Topics
Partitions
Producers
Consumers
Consumer groups
Message keys
Offsets
Replication
KRaft mode
Kafka UI
Retry mechanism
Dead Letter Topic (DLT)
MySQL integration
Docker Compose
Failure handling
Event-driven architecture


Screenshots :-

Producer sends messages to kafka :- 

<img width="890" height="47" alt="image" src="https://github.com/user-attachments/assets/6bf87e92-6a50-4e71-a087-1ad36b6194db" />

Consumer reads messages from kafka server :- 

<img width="829" height="201" alt="image" src="https://github.com/user-attachments/assets/cf6b8a0c-e4ca-45e0-9fa5-45ebbe7082ba" />



CLI commands :- 

1. docker exec -it kafka kafka-topics --list --bootstrap-server localhost:9092 :- to check topics
2. docker exec -it kafka kafka-topics --bootstrap-server localhost:9092 --describe --topic orders :- to get detail of specifc topic
