---
type: paper
title: "Service Management & Orchestration of 5G and 6G Non-Terrestrial Networks"
description: Paper on the requirements for 5G Service Management & Orchestration (SMO) of non-terrestrial networks, motivating TS-SDN-based Radio Intelligence Controllers (RICs) and changes to the 3GPP backend software architecture and interfaces.
resource: https://doi.org/10.1109/AERO53065.2022.9843390
tags: []
sources:
  - resource: https://ieeexplore.ieee.org/abstract/document/9843390
---

# Publication Background

This paper is written by Brian Barritt and Wesley Eddy, the same authors as
the 2015 AIAA SPACE paper that introduced TS-SDN.  At the time of writing,
both authors worked for Meta and participated in the Telecom Infra Project
(TIP) Non-Terrestrial Connectivity Solutions (NTCS) group.

This paper was published in the proceedings of the 2022 IEEE Aerospace
Conference.

# Paper Summary

The Third Generation Partnership Project (3GPP) has been adding support for
Non-Terrestrial Networks (NTN) to the 5G standards, with more NTN features
included between Releases 17 and 18.  The paper argues that to offer NTN
services to users, the 5G Service Management & Orchestration (SMO) functions
will need to direct the physical link topology, routing, and radio resource
management of satellite and airborne nodes in the radio access network.  These
networks may include mobile Integrated Access & Backhaul (IAB) nodes and
mechanically steered, highly directional beams.

These requirements motivate non-real-time and near-real-time Radio
Intelligence Controller (RIC) implementations built on TS-SDN.  The 5G Core
Network will also need to support internetworking with untrusted, non-3GPP
access networks that use existing protocols such as DVB and Link 16.

The paper gives an overview of these new requirements and motivates the
changes needed to the 3GPP backend software architecture and interfaces.  Its
sections cover the problem description, the TS-SDN approach, a unified SMO for
NTN, and related standards and industry activity.

# Bibtex

```
@inproceedings{Barritt2022,
  title     = {Service Management \& Orchestration of 5G and 6G Non-Terrestrial Networks},
  author    = {Brian Barritt and Wesley Eddy},
  year      = {2022},
  pages     = {1--11},
  URL       = {https://doi.org/10.1109/AERO53065.2022.9843390},
  booktitle = {2022 IEEE Aerospace Conference (AERO)}
}
```

# Related References

- [IEEE Xplore page for the paper](https://ieeexplore.ieee.org/document/9843390)
- [Barritt/Eddy AIAA SPACE 2015 paper](barritt-space-2015.md) - Earlier paper introducing the TS-SDN concept.
