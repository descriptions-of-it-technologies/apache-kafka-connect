# Apache Kafka Connect.


## Why Kafka Connect and Streams.
* Four common Kafka use cases:
    * Source => Kafka        Producer API                  Kafka Connect Source
    * Kafka => Kafka         Consumer, Producer API        Kafka Streams
    * Kafka => Sink          Consumer API                  Kafka Connect Sink
    * Kafka => App           Consumer API

* Simplify and improve getting data in and out of Kafka
* Simplify transformation data with Kafka  without relying on external libs



## Why Kafka Connect.
* Programmers always want to import data from the same source:
    * DataBases, JDBC, Couchbase, GoldenGate, SAP HANA, Blockchain, Casandra, DynamoDB, FTP, MongoDB, MQTT, RethinkDB,
      Salesforce, Solar, SQS, Twitter, etc...
* Programmers always want to store data in the same sinks:
    * S3, ElasticSearch, HDFS, JDBC, SAP HANA, DocumentDB, Cassandra, DynamoDB, HBase, MongoDB, Redis, Solr, Splunk, Twitter, etc...
* It is tough to archive Fault Tolerance, Idempotence, Distribution, Ordering.
* Other programmers may already have done a very good job



## Kafka Connect - High level.
* Source connector to get data from Common Data Source.
* Sink Connectors to publish that data in Common Data Source.
* Make its easy for non-experienced dev to quickly get their data reliable into Kafka.
* Part of your ETL pipeline.
* Scaling made easy from small pipelines to company-wide pipelines
* Reusable code.
