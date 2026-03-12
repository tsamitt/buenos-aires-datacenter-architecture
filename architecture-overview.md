# Architecture Overview

The Buenos Aires data center was designed to support a distributed database management system used by a global organization.

The architecture integrates multiple enterprise technologies to ensure high availability, redundancy, and scalability.

Major components include:

Compute Infrastructure
A cluster of Nutanix AHV nodes provides virtualization capabilities for hosting application workloads and database services.

Load Balancing
F5 load balancers distribute client requests across multiple backend servers.

Network Fabric
The switching infrastructure follows a spine-leaf topology, allowing efficient east-west traffic across the data center.

Security
Dedicated firewall appliances enforce network security policies and control access between internal and external systems.

WAN Connectivity
Edge routers provide connectivity between the data center and external network providers.
