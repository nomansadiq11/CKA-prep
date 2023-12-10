

- in namespace all the resouces manager their own
- you can limit the resouces to namespaces
- within namespace service can be accessable just providing the name of the service
- if you want to access the outside service from other namespace yoou need to add namespace int he service name like this
    - db-service.dev(this is namespace).svc.cluster.local
    - this is DNS entry added
- under the mettadata section you can add namespaces to always add that resouces to specfic namespace
- kubectl config set-context $(kubectl config current-context) --namespace=dev
- you can create kind: resoucequota to define the namespace quota


yaml

apiVersion: v1
kind: resoucequota
metadata:
    name: cmputer-quota
    namespace: dev
spec:
    hard:
        pods: "10"
        requests.cpu: "4"
        requests.memory: 5Gi
        limits.cpu: "10"
        limits.memory: 10Gi