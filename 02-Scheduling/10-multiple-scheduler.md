
Multiple Scheduler

- We can create our own kubernetes scheduler
- we can make default or addiontal
- or specfic application can use for that schedule only


yaml

apiVersion: v1
metadata:
    name : my schedule
    namespace
spec:
    containers:
    - command:
        - kube-schedule
        - 