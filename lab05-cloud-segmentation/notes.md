## Goal
Demonstrate basic cloud-style network segmentation.

## Status
Completed.

## Topology
Private PC connected to a switch  
Switch connected to a router  
Router connected to PT Cloud (public network)

## Configuration
Private network uses RFC1918 IPv4 addresses  
Public network uses a different IP subnet  
Router has one interface in each network  
No NAT or firewall rules configured

## What I did
Built two separate networks (private and public)  
Connected them using a router as a Layer 3 boundary  
Assigned IP addresses from different subnets  
Verified connectivity where routing is allowed

## What I learned
Cloud-style networks are segmented by design  
Routers separate networks at Layer 3  
Public and private networks should not be flat  
Different subnets enforce basic isolation  
Connectivity between segments must be explicitly configured  
Private networks are not automatically reachable from public networks

