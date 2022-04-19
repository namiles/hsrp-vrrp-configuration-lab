# Router Redundancy with FHRPs (HSRP/VRRP)
This repository contains router configuration for my HSRP and VRRP configuration labs, available on my blog [here.](#) More free, CCNA labs are availabl at https://nicksnetworklab.com

## HSRP - Hot Standby Router Protocol   

### R1
```
interface GigabitEthernet0/0
  standby 1 ip 10.16.1.252
  standby 1 priority 150
  standby 1 preempt 
```

### R2
```
interface GigabitEthernet0/0
  standby 1 ip 10.16.1.252
  standby 1 preempt 
```

## VRRP - Virtual Router Redundancy Protocol   

### R1
```
interface GigabitEthernet0/0
  
```

### R2
```
interface GigabitEthernet0/0
  
```
