

- DNS

- you can access machine with ip but you can access uisng name by adding DNS name in /etc/hosts file
- with the time this list will grow than you need another server which hold this list we called this as DNS server
- now in our /etc/resolv.config file we add DNS server ip to resolve this
- if local etc hosts file have entory than its its look for DNS server
- you can change the oder in nsswitch.config files dns


- Domain name
    - lets say  you open apps.google.com first its send the request to company DNS server than server find the ip and cache it for if someone request again it will fast fetch this.

- record types
    - A you add the ip of the server
    - AAAA you add the ipv6 of the server
    - CNAME you add the another domain name of the server
- nslookup
    -  you can use nslookup query hostname of the DNS server
    - only goes to DNS file

- Dive
    - same like nslookup
    