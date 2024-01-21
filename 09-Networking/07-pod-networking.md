

- Kubernets does not have build in solution for networking
- for pod networking there will be each network in namespace have a kind of subnet in that subnet all the pods will be created
- for connect all the subnets there will be big cidr which like 10.244.0.0/24 which means all the pods connect together
