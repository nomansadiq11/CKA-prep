
- switching
    - will help to connect two noede or machine
    - two machine needs network interface to connect with switch
    - switch has ip that can get the ip range for both machiens
- router
    - one network to another network to connect we need router
    - its just another device in network, there could be many other devices
- gateway
    - we need to add route in routetable to go other network
    - if there are many routes than you can define 0.0.0.0 in routetable

- Configure linux as router
    - you can allow in linux to forward the packages to eachother
    - /proc/sys/net/ipv4/ip_forward 0 to 1


- Key Commands
    - ip link
    - ip addr
    - ip addr add
    - ip route or route
    - ip add route 