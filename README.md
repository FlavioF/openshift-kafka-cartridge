# OpenShift Kafka Cartridge
This cartridge was created in the scope of understanding how Openshift cartridges work and to provide Kafka in Openshift.

Cartridge Url: https://github.com/FlavioF/openshift-kafka-cartridge/blob/master/metadata/manifest.yml

## About Apache Kafka
Apache Kafka is publish-subscribe messaging rethought as a distributed commit log. [Source](https://kafka.apache.org/)

## Development..
### What is working
- Kafka and Zookeeper runing in same gear. (DONE)
- Kafka and Zookeeper running and communicating in different gears (in same Openshift Application).  (DONE)
- Kafka cluster (DONE)
- Consumer/Producer tests (DONE)

### TO DO
- Add scripts to get and install kafka and zookeeper from the web
- Add scripts to create kafka cluster (automatically)
- Add more env variables
