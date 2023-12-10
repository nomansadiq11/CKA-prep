

- Services
    - to use connect with other services
    - like an applciation have many pods which we can expose using service
    - selector is very important which check which pods to map the services
    - if yor pods are distributed to different nodes service will remain same behavour


yaml

apiVerion: v1
kind: service
metadata:
    name: myapp
spec:
    type: NodePort
    ports:
     - targetPort: 80
       port: 80
       nodePort: 30008
    selector:
        app: myapp
        tier: front-end