# TaskD 3NodeKafkaZookeeper

Implementation of a 3 node Apache Kafka cluster using Docker that demonstrates the Pub-Sub messaging, with a Zookeeper ensemble created to manage the Kafka cluster.

## Prerequisites

Docker

## Instructions to setup

1. Download from this repo
2. Open a command prompt and cd into the folder
3. `docker-compose up`
4. Update the local hosts file
The location of the file for Unix user is at /etc/hosts and for Windows user is at C:\Windows\System32\drivers\etc\hosts
```
Add into the host file "127.0.0.1	kafka-1 kafka-2 kafka-3 zookeeper-1 zookeeper-2 zookeeper-3"
```