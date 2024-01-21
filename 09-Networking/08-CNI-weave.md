- CNI in kubernetes
    - there are set of standards define int he CNI how to use the networking
    - kubelete.service will call these operation when the pod is getting created
    - in the api we mentioenc which cni going to use and there is config file where all the config available to see


- CNI Weave
    - works as daemonset, availabel on each node

- IP address Managment with weave
    -  by default plugin define the cidr
    - and peer divides all the ranges and uses available ips 