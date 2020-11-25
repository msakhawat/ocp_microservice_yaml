Below resources is part of cluster(infrastructure), not application. It is suppose to executed by Cluster Admin. Some of files, like db-credential and git-secret, should not be accesable to everyone.

Create database configmap

`oc apply -f configmap.database.yaml`

Create kafa configmap

`oc apply -f configmap.kafka.yaml`

Create database secret

`oc apply -f secret.db-credential.yaml`

Create git secret

`oc appy -f secret.git-secret.yaml`