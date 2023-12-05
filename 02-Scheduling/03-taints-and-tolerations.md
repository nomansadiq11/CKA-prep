
- here we understand the relationship
- how to pod to restrict to stay with that node to allow


- set the taint to node so no pod will schedule
- taint in the node will not allow any pod to schedule until it tolration but pod can be schedule to another node which doen't have taint
- taint means only node will allow tolartion pods


- taint
    - NoSchedule (do not scheel )
    - prefeernoschedule (avoid schedle )
    - Noexecute (all the existing pod will be evitedt )

- tolations
    - will add to the pods


Note: by default master node set to be taint:noschedule so means not pods should palace here 