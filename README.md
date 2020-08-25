# ad-hoc-routing-protocol

This repository contains 2 implementaions of Wireless Sensor Networks(WSN), ad-hoc routing protocol. 
These were ran on NS-3 network simulators and SUMO visualization tool to assess Transportation system
communication.

1. This approach is based upon reactive routing protocol wherein a mechanism referred by Alternate
Link-based Multipath Reactive Routing (ALM - Reactive) protocol in vehicular ad hoc networks (VANETs) is used.
In this approach, the data transmission is performed by maintaining two disjoint paths. Each path is associated
with their connection termination time (CTT) which is calculated during the path establishment from source to
destination node. Instead of energy consumed by intermediate nodes in the path, connection termination time
is proposed to use for deriving the efficiency of routes. Thisproposed solution reduces the packet drop during the
transmission of data packets due to the availability of a secondary path when the primary path is not available. 
The path gets disconnected due to the mobility of vehicles in VANETs. 

To understand the proposed approach thoroughly, it is divided in several sub sections.

* Path Innovation
* Calculation of Connection Termination Time (CTT)
* Path Alteration
* Path Preservation

2. It is based on LEACH routing protocol which is a clustering based protocol to collect data from wireless network.
It includes distributed cluster formation, local processing to reduce global communication, and randomized rotation 
of the cluster-heads. It performs local data fusion to “compress” the amount of data being sent from the clusters to the base station.
The LEACH network has two phases: the set-up phase and the steady-state phase.


