---
layout: default
---


# What is Orca?

Orca is an efficient multicast forwarding architecture that can support millions
of concurrent multicast sessions in datacenter networks. The
idea of Orca is to *offload* some of the state maintained at
network switches to end servers. To achieve this idea, Orca
computes *fixed-size* and *compact* labels and attaches them to
packets of multicast sessions. These labels effectively enable
shifting some of the data plane tasks to servers. As a result,
Orca significantly reduces the state at switches, minimizes
the bandwidth overhead, incurs small and constant processing
overhead, does not limit the size of multicast sessions, and
eliminates redundant traffic. 

Realizing the proposed server-assisted multicast approach, however, faces multiple challenges
at the control and data planes that Orca addresses. At
the control plane, the proposed architecture needs to calculate
optimized labels, manage state at servers, and handle failures.
At the data plane, it requires packet processing algorithms at
switches and servers that sustain the line-rate performance
and minimize the latency and resource consumption.

# Benefits of Orca

# Proof-of-Concept Implementation

## People

## Source Code


