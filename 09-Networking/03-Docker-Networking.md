

- docker run --network none ngix (this cannot connect wither any other host outside the netjworkg )
- host network
    - hostname is attache the container with host network
    - if you run same instance same ip it will not work becuse same prot
- bridge
    - internal private network created ip
    - create interface for container and namespace for bridge to communicate each other
    - map the port -p 8080 docker host forwar the reques to host
    - docker will do same add the entry to ip tables 
