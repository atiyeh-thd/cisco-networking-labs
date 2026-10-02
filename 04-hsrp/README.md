# HSRP High Availability Lab – Cisco Packet Tracer

## Overview
This project demonstrates the configuration of Hot Standby Router Protocol (HSRP) using Cisco Packet Tracer to provide gateway redundancy and high availability in a local network.
Two Cisco routers are configured to share a virtual IP address and provide a redundant default gateway for end devices. HSRP allows one router to operate as the active router while the other remains in standby mode and takes over if the active router becomes unavailable.

## Key Concepts
* HSRP (Hot Standby Router Protocol)
* First Hop Redundancy
* Gateway Redundancy
* Active and Standby Routers
* Virtual IP Address
* High Availability
* Cisco IOS Configuration
* Network Connectivity Testing

## Network Topology
The topology and configuration were implemented using Cisco Packet Tracer.

## Testing
Connectivity was tested between end devices and the virtual HSRP gateway. Failover was also tested by making the active router unavailable and verifying that the standby router could take over the gateway role.

## Technologies
* Cisco Packet Tracer
* Cisco Routers
* HSRP
* IPv4
* Cisco IOS
