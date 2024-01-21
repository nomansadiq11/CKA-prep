

- Service hosted to accross cluster is know as clusterIP
- nodeport also get the ip but that;s need to access uisng the on the port
- how these happening
    - service are cluster wide concepts
    - as this is not a pod
    - when we create the service its assing the ip, and kubeproxy define ip table any request coming to service ip forwward to pod ip both in cluster ip and noede
    -