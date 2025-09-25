---

# 📘 CCDAK Practice Exam – Apache Kafka Fundamentals (60 Questions)

---

### **Q1.**

In Kafka, what does a partition represent?
A. A mutable sequence of key-value pairs
B. An ordered, immutable sequence of records
C. A relational table row
D. A consumer offset

### **Q2.**

What happens if you create a topic with replication factor 4 in a 3-broker cluster?
A. Topic creation fails
B. Kafka automatically reduces replication factor to 3
C. Kafka adds brokers automatically
D. Kafka creates partitions without replicas

### **Q3.**

Which component in a ZooKeeper-based cluster is responsible for electing the controller?
A. Leader
B. Follower
C. ZooKeeper
D. Producer

### **Q4.**

What does ISR stand for in Kafka?
A. Internal Stream Replication
B. In-Sync Replica
C. Instant State Recovery
D. Indexed Segment Reader

### **Q5.**

The property `log.retention.ms=604800000` means:
A. Messages expire after 7 days
B. Each consumer has 7 days to process a message
C. Kafka retains logs for 7 hours
D. Messages are compacted every 7 hours

### **Q6.**

What is the main purpose of partitions in Kafka topics?
A. Provide data encryption
B. Enable scalability and parallelism
C. Ensure messages are always unique
D. Reduce replication overhead

### **Q7.**

What is the function of the **controller broker** in a Kafka cluster?
A. Stores schemas for all topics
B. Handles leader election and partition reassignment
C. Acts as the only broker receiving writes
D. Manages consumer offsets

### **Q8.**

Which of these is NOT a valid component of Kafka?
A. Producer
B. Broker
C. Queue Manager
D. Consumer

### **Q9.**

The **retention.bytes** property defines:
A. The number of partitions in a topic
B. The maximum size of the log before data is deleted
C. The maximum size of a message
D. The total memory allocated to the producer

### **Q10.**

Kafka’s **append-only log** structure ensures:
A. Random write access to any record
B. Messages in partitions are always strictly ordered
C. Automatic deduplication of messages
D. Real-time indexing of all records

### **Q11.**

What happens when a partition leader fails and no ISR is available?
A. Kafka elects a new leader from out-of-sync replicas
B. Partition becomes unavailable until ISR recovers
C. Messages are lost permanently
D. Producers automatically write to any broker

### **Q12.**

What does a Kafka broker NOT manage?
A. Topic partitions
B. Producer retries
C. Consumer offsets (in KRaft mode)
D. Segment files

### **Q13.**

Which of the following is true about partitions and offsets?
A. Offsets are global across all partitions
B. Each record in a partition has a unique offset
C. Offsets reset when a consumer crashes
D. Offsets are assigned by producers

### **Q14.**

Which feature allows Kafka to act as a **distributed storage system**?
A. Replication
B. Consumer groups
C. Topic compaction
D. Partition offset

### **Q15.**

In Kafka, messages are removed from a partition when:
A. All consumers have read them
B. The retention policy removes them
C. The leader broker crashes
D. The producer requests deletion

### **Q16.**

Which Kafka feature ensures that only one broker is in charge of a partition’s writes?
A. Partition balancing
B. Producer acknowledgment
C. Leader election
D. Log compaction

### **Q17.**

Which of these is true about Kafka topics?
A. A topic can be deleted and recreated with the same name but new partitions
B. Once created, the number of partitions cannot change
C. Topics cannot span multiple brokers
D. A topic always stores data for exactly 24 hours

### **Q18.**

What is the default number of partitions when creating a new Kafka topic (if not specified)?
A. 1
B. 3
C. 5
D. 10

### **Q19.**

What is the difference between **log.retention.ms** and **log.retention.bytes**?
A. One controls retention by time, the other by size
B. Both control time-based retention
C. Both control size-based retention
D. They are synonyms

### **Q20.**

Which Kafka concept is responsible for ensuring **horizontal scalability**?
A. Consumer groups
B. Partitions
C. Replication factor
D. ZooKeeper quorum

### **Q21.**

A broker in the cluster is designated as the **controller**. What happens if it fails?
A. The cluster shuts down
B. A new controller is elected by ZooKeeper
C. All partitions are deleted
D. Producers stop publishing

### **Q22.**

Which statement about Kafka topics is correct?
A. Messages are stored in a relational schema
B. Consumers can change the order of messages in a partition
C. Topics can be configured to delete old data based on time or size
D. Each consumer must read all partitions

### **Q23.**

In a Kafka cluster, what does the term **quorum** mean?
A. Minimum number of partitions per topic
B. Minimum number of brokers that must acknowledge a write
C. Number of consumers in a group
D. Number of producers writing to a topic

### **Q24.**

What is the maximum size of a single Kafka message (without changing configs)?
A. 1 MB
B. 5 MB
C. 10 MB
D. 15 MB

### **Q25.**

Kafka achieves fault tolerance primarily by:
A. Using multiple consumer groups
B. Replicating partitions across brokers
C. Running multiple Zookeeper clusters
D. Compressing data with Snappy

### **Q26.**

Which Kafka topic is used to store internal metadata for partition leadership in **KRaft mode**?
A. `__consumer_offsets`
B. `__transaction_state`
C. `__cluster_metadata`
D. `__leader_epoch`

### **Q27.**

Which of the following is a **compacted topic** best suited for?
A. Log data that grows infinitely
B. Audit logs requiring full history
C. Storing latest values of keys like account balances
D. Binary file storage

### **Q28.**

What happens when a consumer reads from a partition?
A. The broker deletes the message immediately
B. The offset is committed automatically (if enabled)
C. The message is moved to another topic
D. The producer is notified

### **Q29.**

Which of these best describes Kafka’s design principle?
A. Request/response queue
B. Publish/subscribe with distributed log storage
C. Point-to-point messaging only
D. RPC with synchronous acknowledgments

### **Q30.**

If you want to ensure data is not lost when a broker fails, you should:
A. Increase the number of partitions
B. Set replication factor > 1
C. Use `acks=0`
D. Disable log retention

---

### **Q31.**

What does the `unclean.leader.election.enable` setting control?
A. Whether non-ISR replicas can become leader
B. Whether consumers commit offsets automatically
C. Whether producers retry failed requests
D. Whether ZooKeeper elects a new broker

### **Q32.**

Kafka stores messages on disk because:
A. Memory is unreliable
B. Sequential disk writes are very fast
C. Kafka does not support memory caching
D. Disk storage ensures at-most-once delivery

### **Q33.**

Which is true about offsets?
A. Each partition has independent offsets starting at 0
B. Offsets are shared across partitions
C. Offsets are global across all topics
D. Offsets are always random

### **Q34.**

What is the minimum number of brokers required for replication factor = 3?
A. 1
B. 2
C. 3
D. 4

### **Q35.**

Which of these is NOT stored by Kafka brokers?
A. Topic partitions
B. Producer keys
C. Log segments
D. Replica state

### **Q36.**

Kafka’s ability to replay messages comes from:
A. Retention policies
B. Log compaction
C. Offsets
D. All of the above

### **Q37.**

Which of these is true about Kafka segments?
A. They are fixed-size log files
B. They are deleted after every consumer read
C. They are replicated by ZooKeeper
D. They contain schema definitions

### **Q38.**

What is the role of replication factor?
A. Control message size
B. Ensure fault tolerance by duplicating partitions
C. Speed up consumer reads
D. Allow multiple producers per topic

### **Q39.**

Which scenario requires enabling log compaction?
A. Transactional systems needing latest account balance
B. IoT telemetry data ingestion
C. Archiving system logs for 7 years
D. Real-time video streaming

### **Q40.**

The default cleanup policy for Kafka topics is:
A. Delete
B. Compact
C. Retain forever
D. Compress

### **Q41.**

Which Kafka tool lists available topics?
A. `kafka-topics.sh`
B. `kafka-console-consumer.sh`
C. `kafka-acls.sh`
D. `zookeeper-shell.sh`

### **Q42.**

Which Kafka file format stores log data on disk?
A. JSON
B. Log segments (.log files)
C. Avro
D. CSV

### **Q43.**

If replication factor = 1 and the broker fails, what happens?
A. Messages are unavailable until broker restarts
B. ISR replicas take over
C. Producers continue unaffected
D. Messages are migrated to another broker

### **Q44.**

Kafka consumer lag means:
A. Consumers are reading faster than producers write
B. Consumers are behind the latest producer offset
C. Brokers are running out of disk space
D. ZooKeeper is overloaded

### **Q45.**

Which is true about topic deletion in Kafka?
A. Deletes all log files for that topic
B. Leaves offsets behind
C. Is not possible without ZooKeeper
D. Automatically creates a new topic

### **Q46.**

What is the default file system for Kafka logs?
A. ext4/xfs (any local disk FS)
B. HDFS
C. Object storage (S3)
D. In-memory FS

### **Q47.**

Which of these is NOT a Kafka guarantee?
A. Order within a partition
B. Durability of committed messages
C. At-least-once delivery by default
D. Global ordering across partitions

### **Q48.**

Which Kafka property sets default replication for new topics?
A. `num.partitions`
B. `offsets.topic.replication.factor`
C. `default.replication.factor`
D. `min.insync.replicas`

### **Q49.**

Kafka metadata about brokers and partitions is shared via:
A. ZooKeeper (pre-KRaft) or internal metadata topic (KRaft)
B. Schema Registry
C. Producer configs
D. OS system logs

### **Q50.**

The `acks=all` setting ensures:
A. No acknowledgment
B. Leader only acknowledgment
C. Acknowledgment after all ISR replicas confirm
D. Acknowledgment after consumer reads

### **Q51.**

Which factor most influences partition throughput?
A. Number of brokers
B. Number of partitions
C. Replication factor
D. ZooKeeper nodes

### **Q52.**

Kafka achieves high throughput mainly due to:
A. Sequential disk writes and zero-copy transfer
B. Replication
C. Log compaction
D. ZooKeeper quorum

### **Q53.**

Which scenario causes partition rebalance?
A. Consumer joins or leaves a group
B. Producer sends too many messages
C. Broker deletes logs
D. Topic retention expires

### **Q54.**

Which is the smallest unit of storage in Kafka?
A. Topic
B. Partition
C. Offset
D. Segment

### **Q55.**

Which property controls maximum batch size for producers?
A. `max.request.size`
B. `batch.size`
C. `linger.ms`
D. `compression.type`

### **Q56.**

Kafka uses checksums for:
A. Verifying data integrity of messages
B. Encrypting messages
C. Rebalancing consumers
D. Hashing keys

### **Q57.**

Which Kafka feature prevents message loss during broker crashes?
A. Replication
B. Retention policy
C. Log compaction
D. Batch.size

### **Q58.**

Which scenario breaks Kafka’s ordering guarantee?
A. Multiple partitions with same key
B. Multiple consumers in a group
C. A single producer sending to a single partition
D. Leader election

### **Q59.**

Which tool checks partition offsets for a consumer group?
A. `kafka-consumer-groups.sh`
B. `kafka-topics.sh`
C. `kafka-acls.sh`
D. `kafka-configs.sh`

### **Q60.**

Which property ensures only committed messages are read by consumers?
A. `isolation.level=read_committed`
B. `enable.auto.commit=true`
C. `auto.offset.reset=earliest`
D. `acks=all
