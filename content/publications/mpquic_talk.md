---
title: " A Multipath Extension to the QUIC Module in ns-3"
date: 2022-06-15
pubtype: "Talk"
featured: true
tags: ["MPQUIC","Network Simulation","ns-3","Transport Protocols"]
# image: "/img/organicdevops.webp"
# link: "http://www.alldaydevops.com/blog/organically-devops-building-quality-and-security-into-the-software-supply-chain-at-liberty-mutual"
# fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 400
sitemap:
  priority : 0.5
---

Network transmission with multiple interfaces is desirable for the next-generation Internet to improve end-to-end performance and reliability. Multipath QUIC (MPQUIC) is proposed to utilize multiple access links and paths for non-interrupted Internet transmission building upon QUIC, a newly standardized transport layer protocol. The lightning talk will describe the current effort to develop a multipath extension to the QUIC module in ns-3. This extension has the scalability of multiple paths, the flexibility of the path schedulers, and the extensibility of the congestion control algorithms, providing a stable simulation platform for the research community on multipath transport layer protocols. The development of MPQUIC overcomes the challenges of advertising multiple addresses, separating transmission paths, and extending the scheduling and congestion control algorithms, while still maintaining the fundamental transmission features. The result verifies the correctness of the implementation and showcases the performance of MPQUIC with a set of experimentations. This effort is underway; we will further implement the currently missing functions in MPQUIC ns-3 and keep updating it according to the IETF draft. Exploring better scheduling and congestion control algorithms will also be considered in our future work. This is joint work with my collaborators Wenjun Yang, Jianping Pan, and Lin Cai.


<!-- {{< youtube id="FsfKsqI07jM" t="80" width="600px" >}} -->
