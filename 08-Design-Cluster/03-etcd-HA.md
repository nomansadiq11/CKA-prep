

- We can create multple database servers
- read from all the nodes are fine
- write to all the nodes will be complext
- so the write comes to the node it reirect to the writer leaer to write to the ddatabase and leader responsible to propagate other noes also


- how the leader electe
    - RAFT alogo
        - node initiae the election preocess to send request
- how the copy the data


- Quorum = N/2 + 1 = this is write completed if the leader able to write following number of the nodes
- 