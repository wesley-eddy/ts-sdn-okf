---
type: paper
title: "The Modeling, Simulation, and Operational Control of Aerospace Communication Networks"
description: Brian Barritt's PhD dissertation on simulating aerospace communication networks during design and controlling them in operation with TS-SDN, with application to LEO satellite constellations and High Altitude Platform Systems (HAPS).
resource: http://rave.ohiolink.edu/etdc/view?acc_num=case1499348546519051
tags: []
sources:
  - resource: https://etd.ohiolink.edu/acprod/odb_etd/etd/r/1501/10?clear=10&p10_accession_num=case1499348546519051
---

# Publication Background

This is Brian Barritt's Doctor of Philosophy dissertation in Computer
Engineering (EECS), completed at Case Western Reserve University in 2017.
The committee was chaired by Frank Merat, with Michael Rabinovich, Daniel
Saab, and Mark Allman as members.

The author worked at Google on the Project Loon and Titan Aerospace networks,
and co-authored the earlier papers that introduced TS-SDN.

# Paper Summary

The dissertation starts from a shift in aerospace communications.  Older
systems used circuit switching, with geostationary satellites acting as
bent-pipe transponders.  Growing mission complexity and NewSpace practices
are pushing toward packet-based networks.  New networks in non-geostationary
orbits or the upper atmosphere aim to provide low-latency imaging or Internet
access, and rely more on beamforming, narrow beams, and free-space optical
links.

For the design phase, the dissertation argues for evaluating these networks
with network simulators rather than relying only on link budget calculations.
It presents a simulation approach that integrates with spatial temporal
information systems for high-fidelity modeling of the physical layer.

For operational control, it describes TS-SDN.  TS-SDN uses the predictable
motion of network platforms to build a predictive view of the network
topology, and extends the SDN southbound interface to schedule synchronized
future state changes, which helps tolerate delay and disruption in the
control plane.  The dissertation outlines a TS-SDN implementation at Alphabet
and shows its benefits for LEO satellite constellations and High Altitude
Platform Systems (HAPS).

# Bibtex

```
@phdthesis{Barritt2017PhD,
  title  = {The Modeling, Simulation, and Operational Control of Aerospace Communication Networks},
  author = {Brian James Barritt},
  year   = {2017},
  school = {Case Western Reserve University},
  URL    = {http://rave.ohiolink.edu/etdc/view?acc_num=case1499348546519051}
}
```

# Related References

- [OhioLINK copy of the dissertation (PDF)](https://etd.ohiolink.edu/acprod/odb_etd/ws/send_file/send?accession=case1499348546519051&disposition=inline)
- [Barritt/Eddy AIAA SPACE 2015 paper](barritt-space-2015.md) - Earlier paper introducing the TS-SDN concept.
