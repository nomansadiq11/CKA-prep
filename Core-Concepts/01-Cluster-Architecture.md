
Cluster Architecture

There are noes
    - master Node
        - Manage the cluste node add and remove the pods
        - master node have ETCD db which store the inform ation about the pods are store on which node
        - master node have schedule which schedule the pods on noes
        - master node have controller
            - node controller, handle the nodes
        - replication controller which check the replication of the pods
        - KubeAPI server primary management for the cluster, its for external user for managment of the cluster,
        - Kubernet have runtime envirment, docker, containerd and rocket

    - Cluster nodes which holds the containers
        - kubelets run on each node which run pods, which pull the states from master node its like captan
        - kube-proxy server to allow to commnication services earch other with in the cluster 