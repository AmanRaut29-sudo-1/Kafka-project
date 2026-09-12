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


CLI commands :- 

1. docker exec -it kafka kafka-topics --list --bootstrap-server localhost:9092 :- to check topics
2. docker exec -it kafka kafka-topics --bootstrap-server localhost:9092 --describe --topic orders :- to get detail of specifc topic
