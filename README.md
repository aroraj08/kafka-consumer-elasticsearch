# kafka-consumer-elasticsearch

This sample application is a Kafka consumer, which reads data from Kafka broker. The topic in Kafka broker contains tweets feed from Twitter for specific terms.
The consumer polls for data every 100 ms and pushes the data into Elastic Search data store. The Elastic Search Data store is hosted on Bonsai for this application.

