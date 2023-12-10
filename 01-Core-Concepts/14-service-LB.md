

- Loadbalancer
    - We create the service type of the Loadbalancer
    - for the internal access the service we are using nodePort but if we want to use external we need to use loadbalancer
    - kubenetes have native to previoust he loadbalancer on the cloud by using type using loadbalancer


yaml

apiVersion: v1
kind: service
metadata:
    name: svc
spec:
    type: loadBalancer
    ports:
        - tartgetPort: 80
          port: 80
          nodePort:30008