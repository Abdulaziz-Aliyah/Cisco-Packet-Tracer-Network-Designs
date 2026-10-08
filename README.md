# Cisco-Packet-Tracer-Network-Designs
Multi-router network topologies with subnetting, built and tested in Packet Tracer
# Cisco Packet Tracer Network Designs

A set of network topologies built and tested in Cisco Packet Tracer to practice routing, subnetting, and multi-device network design.

## Tools
Cisco Packet Tracer

## Topologies included
- Four-router ring network: Four routers connected in a ring across separate subnets (192.168.12.0/24, .13, .24, .34), with end devices on each side, tested with ICMP pings
- Campus network (ABC Institute): A central switch connecting access points, a wireless router, and a server, serving separate groups (Admin/ICT lab, staff laptops, smartphones, Guest Wi-Fi)
- Three-router LAN interconnect: Two LANs connected through three routers over serial links, tested with pings between hosts

## What I learned
Subnetting and IP addressing across multiple routers, basic routing between networks, and designing a network with logical separation between user groups (useful for segmentation and access control thinking).

## Possible improvements
Add routing protocol configuration (OSPF/EIGRP) documentation, include ACLs restricting traffic between the Guest Wi-Fi segment and the rest of the network.