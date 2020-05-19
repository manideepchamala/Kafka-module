# Kafka-module
## Manideep Chamala

## Commands that i used

1. ```.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties``` 
This command is used to run ZooKeeper service.
1. ```.\bin\windows\kafka-server-start.bat .\config\server.properties```
This command is used to run a kafka service.
1. ```.\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --create --topic Cricket``` To create a topic Cricket in kafka.
1. ```.\bin\windows\kafka-topics.bat --zookeeper localhost:2181 --list```  This is used to display the list of topics.
1. ```.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic Cricket```  This command is used to run kafka producer.
1. ```.\bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic Cricket --from-beginning``` Runs kafka consumer and shows messages from beginning.
