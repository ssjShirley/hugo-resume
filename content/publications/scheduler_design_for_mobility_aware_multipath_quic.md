---
title: "Scheduler Design for Mobility-aware Multipath QUIC"
date: 2022-12-04
pubtype: "Conference Paper"
featured: true
description: "W. Yang, L. Cai, S. Shu and J. Pan, \"Scheduler Design for Mobility-aware Multipath QUIC,\" 2022 IEEE Global Communications Conference (GLOBECOM), Rio de Janeiro, Brazil, 2022, pp. 2849-2854, doi: 10.1109/GLOBECOM48099.2022.10001247."
tags: ["Out-of-order","Multipath","Goodput","Mobility","Scheduling"]
link: "https://ieeexplore.ieee.org/abstract/document/10001247"
weight: 400
sitemap:
  priority : 0.8
---
W. Yang, L. Cai, **S. Shu** and J. Pan, \"Scheduler Design for Mobility-aware Multipath QUIC,\" 2022 IEEE Global Communications Conference (GLOBECOM), Rio de Janeiro, Brazil, 2022, pp. 2849-2854, doi: 10.1109/GLOBECOM48099.2022.10001247.

Abstract: The Integrated Terrestrial and LEO satellite network (ITSN) is promising for providing ubiquitous communication services. In ITSN, network mobility brings new challenges and attracts attention. In this paper, we promote a new transport layer protocol, Multipath QUIC (MPQUIC) to deal with the network mobility issue in ITSN. ITSN is characterized by high bandwidth delay product (BDP). The standard congestion control algorithm of MPQUIC, Opportunistic Linked Increases Algorithm (OLIA), encounters great challenges such  as congestion window (cwnd) overshooting whenever handoff, which motivates our proposal, a Mobility-aware Multipath QUIC (MM-QUIC) congestion control algorithm. MM-QUIC leverages the periodical changes of path capacity and good similarity among disjoint subflows to quickly start a new round of transmission, and employs a multipath-based fluid model to determine the cwnd adjustment in the congestion avoidance phase. Finally, simulation results on NS-3 demonstrate that MM-QUIC can offer up to 50% throughput improvement compared to OLIA in ITSN.

<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
