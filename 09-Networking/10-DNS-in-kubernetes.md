

- DNS resolution within the cluster
    - kube-DNS service create a records for service
    - kube-dns define the dns records
    - service-name.namespace.svc.cluster.local
    - same we can enable for pods also
    - so the pods will be like pod-ip.namespace.pod.cluster.local


- CoreDNS
    - will deployed in kubernets
    - there is confiuration define /etc/coredns/corefile
    - any request call its forwar to coredns 