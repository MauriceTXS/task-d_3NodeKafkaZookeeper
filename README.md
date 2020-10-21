# TaskD 3NodeKafkaZookeeper

Implementation of a 3 node Apache Kafka cluster using Docker that demonstrates the Pub-Sub messaging, with a Zookeeper ensemble created to manage the Kafka cluster.

## Prerequisites

Docker

## Instructions to setup

1. Download from this repo
2. Open a command promp and cd into the folder
3. `docker-compose up`
4. Edit the local hosts file. 
```
For Unix user /etc/hosts and for Windows user C:\Windows\System32\drivers\etc\hosts.
Add into the host file "127.0.0.1	kafka-1 kafka-2 kafka-3 zookeeper-1 zookeeper-2 zookeeper-3"
```