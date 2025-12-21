## Goal
Demonstrate NAT overload (PAT) with multiple internal hosts.

## Status
Completed.

## Topology
- 3 PCs connected to a switch
- Switch connected to a router
- Router connected to PT Cloud (simulated Internet)

## Configuration
- PCs use private IPv4 addresses
- Router configured for NAT overload
- One external interface represents public access

## What I did
- Built a small LAN with multiple end devices
- Configured a router to translate private IPs to a single external IP
- Verified external connectivity from internal hosts

## What I learned
- NAT allows private networks to access external networks
- NAT overload enables multiple devices to share one public IP
- NAT is a network function, not just a physical device
- NAT requires: Inside interface, Outside interface, Nat rule, Routing
- This concept requires more study and will be revisited later
