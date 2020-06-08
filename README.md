# NiFItoKafkaConnect

NiFi -> Kafka Connect -> HDFS

# Configuration To Change

## "hdfs.uri": "hdfs://CDPAWSIP:8020",

# "tasks.max": "1",

# "topics": "test3",

# "value.converter.schema.registry.url": "http://CDPAWSIP:7788/api/v1",

# "hdfs.output": "/tmp/sensors/"

You specify the **Kafka topic(**s). You set an **HDFS** URI. You pick the directory, it will construct subdirectories below that. You specify Cloudera **Schema Registry URL**. You can also set Kubernetes settings as well.

For NiFi Kafka Producer:

**AvroRecordSetWriter**

*   _**HWX Content-Encoded Schema Reference**_
*   _**Inherit Record Schema**_
*   _Schema Registry_

**References**

*   [https://docs.cloudera.com/runtime/7.1.1/kafka-connector-reference/topics/kafka-connector-reference-s3.html](https://docs.cloudera.com/runtime/7.1.1/kafka-connector-reference/topics/kafka-connector-reference-s3.html)
*   [https://docs.cloudera.com/runtime/7.1.1/kafka-connector-reference/topics/kafka-connector-reference-hdfs.html](https://docs.cloudera.com/runtime/7.1.1/kafka-connector-reference/topics/kafka-connector-reference-hdfs.html)
