## Goal
Demonstrate routing between two different IPv4 subnets.

## Status
Completed.

## Topology
PC1 -- Switch -- Router -- Switch -- PC2

## IP Configuration
Subnet A:
- PC1: 192.168.1.10 / 255.255.255.0
- Default Gateway: 192.168.1.1

Subnet B:
- PC2: 192.168.2.10 / 255.255.255.0
- Default Gateway: 192.168.2.1

Router:
- Interface to Subnet A: 192.168.1.1 / 24
- Interface to Subnet B: 192.168.2.1 / 24

## What I did
- Built two separate LANs using different IPv4 subnets
- Configured router interfaces with IP addresses in each subnet
- Assigned static IP addresses to both PCs
- Set the router as the default gateway on each PC

## Tests
- Ping from PC-Subnet1 to PC-Subnet2 successful
- Ping from each PC to its default gateway successful

## What I learned
- Switches operate within a single subnet (Layer 2)
- Routers connect different subnets (Layer 3)
- Devices in different networks require a router to communicate
- The default gateway enables traffic to leave the local subnet
- The difference between a Subnet and a Subnetmask

