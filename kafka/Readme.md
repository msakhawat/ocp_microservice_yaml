Create cluster

`oc apply -f kafka-cluster.yaml`

Create topic

`oc apply -f kafka-topic.yaml`

Create user for producer

`oc apply -f kafka-user.producer.yaml`

Create user for consumer

`oc apply -f kafka-user.consumer.yaml`
