---
title: "MM-QUIC: A mobility-aware multipath QUIC for satellite networks"
date: 2021-12-08
pubtype: "Conference Paper"
featured: true
description: "W. Yang, S. Shu, L. Cai, J. Pan, \"MM-QUIC: A mobility-aware multipath QUIC for satellite networks,\" 17th IEEE International Conference on Mobility, Sensing and Networking (MSN'21, virtual), invited paper, Dec. 2021."
# tags: ["DevOps","Continuous Integration","Continuous Delivery","CI/CD pipelines","agile","Culture"]
# image: "/img/organicdevops.webp"
# link: "http://www.alldaydevops.com/blog/organically-devops-building-quality-and-security-into-the-software-supply-chain-at-liberty-mutual"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.8
---

Abstract: The Integrated Terrestrial and LEO satellite network (ITSN) is promising for providing ubiquitous communication services. In ITSN, network mobility brings new challenges and attracts attention. In this paper, we promote a new transport layer protocol, Multipath QUIC (MPQUIC) to deal with the network mobility issue in ITSN. ITSN is characterized by high bandwidth delay product (BDP). The standard congestion control algorithm of MPQUIC, Opportunistic Linked Increases Algorithm (OLIA), encounters great challenges such  as congestion window (cwnd) overshooting whenever handoff, which motivates our proposal, a Mobility-aware Multipath QUIC (MM-QUIC) congestion control algorithm. MM-QUIC leverages the periodical changes of path capacity and good similarity among disjoint subflows to quickly start a new round of transmission, and employs a multipath-based fluid model to determine the cwnd adjustment in the congestion avoidance phase. Finally, simulation results on NS-3 demonstrate that MM-QUIC can offer up to 50% throughput improvement compared to OLIA in ITSN.

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
