# kafka
Apache kafka commands

1. To start zookeeper (Locate zookeeper-server-start.bat from bin/windows folder and zookeeper.properties from config folder)
   bin/windows/zookeeper-server-start.bat config/zookeeper.properties
   
   default start port : 2181

2. To start kafka server (Locate kafka-server-start.bat from bin/windows folder and server.properties from config folder)
   bin/windows/kafka-server-start.bat config/server.properties
   
   default start port : 9092
   
3. To create kafka topic
   bin/windows/kafka-topics.bat --bootstrap-server localhost:9092 --create --topic rkjavahub-topic --partition 3 --replication-factor 1

4. To get the list of topics
   bin/windows/kafka-topics.bat --bootstrap-server localhost:9092 --list
   
5. To describe the topic (Get more details of topic such as partition, leader, replicas)
   bin/windows/kafka-topics.bat --bootstrap-server localhost:9092 --describe --topic rkjavahub-topic

6. 
   
