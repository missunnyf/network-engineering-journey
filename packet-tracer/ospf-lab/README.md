# OSPF Lab

## Goal

What this lab sets out to demonstrate (e.g., single-area OSPF between 3 routers).

## Topology

!\[OSPF Lab Topology](../diagrams/ospf-lab-topology-day1.png)

## Devices

* Cisco 2911 routers (x2)
* Cisco 2960 switches (x2)
* Cisco 5505 Firewalls (x2)
* PCs (x2)
* Servers (x2)
* Laptop labeled as the 'attacker' 
* Packet Tracer's 'Automatically Choose Connection Type' function

## Key configs

```
router ospf 1
 network 192.168.1.0 0.0.0.255 area 0
```

## What I learned / issues hit

* How to showcase how one location connects to the internet and then connects to another location. What order network devices should/can be setup as. As well as the function of device. 

