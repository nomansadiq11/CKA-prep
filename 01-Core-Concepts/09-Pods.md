

 - Containers add in side the pods
 - you want more containrs we scalu up pods
 - we can create side-car containers inside the pods
 - both containers both can communication with each other using local host

 - Pods with YAML
    apiVersion: v1
    Kind: pod
    metadata:
        name: my-app
        labels:
            app: test
            type: front-end
    spec:
        containers: -- its list
        - name: nginx-container
          image: nginx
          
- in metadata field only specfi which kubernets expects