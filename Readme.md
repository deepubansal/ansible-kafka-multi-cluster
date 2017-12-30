This repository contains an ansible playbook to provision 8 plain Centos machines to replicate a multi-kafka-cluster environment. A Kafka cluster has few broker nodes and a zookeeper node to provide coordination among these brokers in the cluster. The use case was to acess these clusters via a cluster of tomcat servers. So the script also installs tomcat server on few of the nodes.

The exact configuration looks like:


| Node | Java | Tomcat | Zookeeper | Kafka Broker |
|--|--|--|--|--|
| node1 | Jdk8 | tomcat1 |  | Broker11 |
| node2 | Jdk8 |  | zk1 | Broker12|
| node3 | Jdk8 | tomcat2 |  | Broker21|
| node4 | Jdk8 |  | zk2 | Broker22|
| node5 | Jdk8 |  |  | Broker23|
| node6 | Jdk8 | tomcat3 |  | Broker31|
| node7 | Jdk8 |  | zk3 | Broker32|
| node8 | Jdk8 |  |  | Broker33|
 
 Broker'***ij*** defines the broker ***j*** in cluster ***i*** managed by zookeeper zk'***i***.

This script was written 2 years ago so need some updation as per newer version of ansible and centos.
