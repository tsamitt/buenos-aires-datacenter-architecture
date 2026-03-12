# Buenos Aires Data Center Architecture

## Overview

This project presents the architecture design of a regional data center located in Buenos Aires, Argentina. The data center is designed to support a distributed database management system (DDBMS) and global private cloud infrastructure for enterprise applications.

The architecture incorporates modern data center networking principles including spine–leaf switching, virtualization clusters, load balancing, and layered security controls.

## Architecture Layers

The design follows a layered architecture commonly used in enterprise data centers.

Compute Layer
Virtualization hosts running Nutanix AHV provide the compute infrastructure for application services and database nodes.

Load Balancing Layer
F5 load balancers distribute incoming application traffic across backend services to ensure performance, scalability, and availability.

Network Fabric Layer
A spine–leaf network topology provides high-speed east–west traffic between servers and minimizes network latency.

Security Layer
Enterprise firewalls enforce security policies and control traffic between internal infrastructure and external networks.

WAN Edge Layer
Edge routers connect the data center to global network providers and other company locations.

## Key Technologies

Nutanix AHV Virtualization  
F5 Load Balancing  
Spine–Leaf Data Center Networking  
Enterprise Firewalls  
WAN Edge Routing  

## Design Goals

High availability  
Fault tolerance  
Low latency east-west traffic  
Scalable infrastructure  
Secure network segmentation  

## Diagram

![Data Center Architecture](diagrams/buenos-aires-datacenter.png)

## What I Learned

Through this project I learned how enterprise data centers are designed to support distributed systems, virtualization platforms, and large-scale application services.

The architecture demonstrates how networking, virtualization, security, and load balancing components work together to provide reliable infrastructure.
