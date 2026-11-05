---
type: paper
title: "Operating a UAV Mesh & Internet Backhaul Network using Temporospatial SDN"
description: Paper applying TS-SDN to UAV mesh and backhaul networks, describing Google's TS-SDN implementation and comparing it to distributed mesh routing.
resource: https://ieeexplore.ieee.org/document/7943701/
tags: []
sources:
  - resource: https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45948.pdf
---

# Publication Background

This paper is written by Google engineers who worked on the Titan Aerospace
and Project Loon airborne networks.

This paper was published in the proceedings of the 2017 IEEE Aerospace
Conference.

# Paper Summary

The paper applies TS-SDN to networks of UAVs and other airborne platforms that
provide direct-to-user access and Internet backhaul, linked to ground stations
by narrow, steerable beams.  It explains why these networks need centralized
topology control: platforms move, weather changes, and steering beams to
acquire a link takes several seconds, so reactive repair is costly.

It then describes Google's TS-SDN implementation.  A network data model
serves as a shared state and API between SDN applications, and a new,
OpenFlow-inspired control protocol supports state changes scheduled for a
future time, as well as control of beam steering and radio parameters.

Finally, the paper compares TS-SDN routing to the AODV, DSDV, and OLSR mesh
routing protocols in ns-3 simulations of 487 UAVs and 38 ground stations.
Distributed routing disrupts traffic for 20 msec to 2 seconds on every
topology change, while TS-SDN can avoid these disruptions by rerouting traffic
ahead of predicted link changes.  Distributed routing remains useful as a
fallback when a node loses contact with the controller.

# Bibtex

```
@inproceedings{Barritt2017,
  title     = {Operating a UAV Mesh \& Internet Backhaul Network using Temporospatial SDN},
  author    = {Brian Barritt and Tatiana Kichkaylo and Ketan Mandke and Adam Zalcman and Victor Lin},
  year      = {2017},
  pages     = {1--7},
  URL       = {https://ieeexplore.ieee.org/document/7943701/},
  booktitle = {2017 IEEE Aerospace Conference}
}
```

# Related References

- [Google's page on the paper](https://research.google/pubs/operating-a-uav-mesh-internet-backhaul-network-using-temporospatial-sdn/)
- [Google's copy of the paper](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45948.pdf)
