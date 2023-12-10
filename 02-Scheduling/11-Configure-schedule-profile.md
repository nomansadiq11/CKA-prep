

- Pods are schedule base on priotity class
- than it will filter the node which has require space like 10 vcpu for those node available
- than there will be scoring on noede after consume 10 vup which node wil have high cpu than it will be selelcted
- unscheduleabel nodes also filter out
- if there is any nodename define in the pod deployment
- while scoring the node, check node already have image locality
- we can define multiple profiles to schedule to schedule the pods, this is very important schedule can overlap the configuration



<img src="11.1.png" />
