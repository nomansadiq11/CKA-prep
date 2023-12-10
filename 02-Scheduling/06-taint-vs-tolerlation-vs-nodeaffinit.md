

- when you taint the node you are not gurantee that will will comes here only
- when you do only node affinity you are not sure that other pods can come here
- for this you will have to select both condition for this
    - taint your node and pods to comes to that nodes only
    - than add node-affinity to specfi to that node only
    