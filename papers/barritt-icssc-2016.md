---
type: paper
title: "SDN Enhancements for LEO Satellite Networks"
description: Paper on the advantages of SDN over dynamic routing protocols for controlling large low-earth orbit (LEO) satellite constellations, with simulation results showing why dynamic routing protocols do not work well at that scale.
resource: https://doi.org/10.2514/6.2016-5755
tags: []
sources:
  - resource: https://arc.aiaa.org/doi/pdf/10.2514/6.2016-5755
---

# Publication Background

This paper is written by Brian Barritt (Google) and Wesley Eddy (MTI
Systems), the same authors as the 2015 AIAA SPACE paper that introduced
TS-SDN.

This paper was published in the proceedings of the 34th AIAA International
Communications Satellite Systems Conference (ICSSC) in October 2016, in the
Internetworking and Communications session.

# Paper Summary

Routing in large LEO communications satellite constellations has been studied
since the 1990s and remains a hard problem.  Newly proposed constellations
involve hundreds of spacecraft at relatively low altitudes, and aim to serve
several orders of magnitude more ground users than earlier systems.

The paper describes the aspects of SDN that motivate its use in LEO
constellations and that improve on other ways of managing network layer
routing and forwarding, such as the dynamic routing protocols previously
studied for large LEO systems.  It presents simulation results showing the
problems with traditional use of dynamic routing protocols, and why they will
never work well for large LEO constellations.  These results provide a
baseline for comparison with the performance an SDN-based system can achieve.

# Bibtex

```
@inproceedings{Barritt2016LEO,
  title     = {SDN Enhancements for LEO Satellite Networks},
  author    = {Brian Barritt and Wesley Eddy},
  year      = {2016},
  note      = {AIAA 2016-5755},
  URL       = {https://doi.org/10.2514/6.2016-5755},
  booktitle = {34th AIAA International Communications Satellite Systems Conference}
}
```

# Related References

- [AIAA abstract page for the paper](https://arc.aiaa.org/doi/abs/10.2514/6.2016-5755)
- [Barritt/Eddy AIAA SPACE 2015 paper](barritt-space-2015.md) - Earlier paper introducing the TS-SDN concept.
- [Barritt et al. IEEE Aerospace Conference 2017 paper](barritt-aeroconf-2017.md) - Cites this paper for TS-SDN in LEO satellite networks.
