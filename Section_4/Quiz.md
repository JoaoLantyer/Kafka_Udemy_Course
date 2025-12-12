### Question 1:

Kafka topics...

a) always have 1 partition

b) can have as many partitions as desired <-

### Question 2:

Offsets are only relevant at the level of

a) the topic

b) the topic-partition <-

### Question 3:

Once sent to a topic, a message can be modified

a) true

b) false <-

### Question 4:

Brokers are identified by

a) A name (string)

b) An ID (number) <-

### Question 5:

Every broker

a) contains all the topics and all the partitions

b) contain only a subset of the topics and the partitions <-


### Question 6:

If a topic has a replication factor of 3

a) Each partition will live on 3 different brokers <-

b) Each partition will live on 2 different brokers

c) Each partition will live on 4 different brokers


### Question 7:

If a topic has a replication factor of 3, what maximum number of brokers can be stopped without impacting the topic availability?

a) 1

b) 2 <-

c) 3

### Question 8:

Each partition can only have 1 leader, and multiple replicas

a) true <-

b) false


### Question 9:

To produce data to a topic, a producer must provide the Kafka client with...

a) any broker from the cluster and the topic name <-

b) any broker from the cluster and the topic name and the partitions list

c) all the brokers from the cluster and the topic name

d) the list of brokers that have the data, the topic name, and the partitions list

### Question 10:

To get acknowledgment of writes to only the leader, we need to use the config...

a) acks=1 <-

b) acks=0

c) acks=all

### Question 11:

To read data from a topic, the following configuration is needed for the consumers

a) any brokers to connect to, and the topic name <-

b) all brokers of the cluster, and the topic name

c) any brokers, and the list of topic partitions

### Question 12:

Two consumers that have the same group.id (consumer group id) will read from mutually exclusive partitions

a) true <-

b) false

### Question 13:

Kafka Consumer Offsets are stored in...

a) Zookeeper

b) Kafka <-