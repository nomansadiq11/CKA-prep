

- Replication Controllers
    - if pods fail this will bring new pods
    - create multiple pods to share the load on multiple loads


YAML - replicaset


apiVersion: apps/v1
kind: ReplicaSet
metadata:
    name: myapp-rs
    labels:
        app: myapp
spec:
    template:
        metadata:
            app: test
        spec:
            containers:
                - name: test
    replicas: 3
    selector:
        matchLabels:
            app: test // this should match with pod lables

- scale the replicaset
    - first update the number of the replica number 6
    - 
