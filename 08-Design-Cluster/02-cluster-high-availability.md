

- master node hosting following
    - ETCD
    - api server
    - controller manager
    - scheduler


- leader election process: which means active and passsive mode
    - process will update end point leader elect true
    - its been ative for 15s
    - its reelect within 10s
    - reader elect retry period 2s