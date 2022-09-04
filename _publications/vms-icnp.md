---
title: "VMS: Traffic balancing based on virtual switches in datacenter networks"
collection: publications
permalink: /publication/vms-icnp
excerpt: 'Zhaogeng Li, Jun Bi, Yiran Zhang, Abdul Basit Dogar, Chengwei Qin'
date: 2017-10-30
venue: 'IEEE International Conference on Network Protocols (ICNP)'
paperurl: 'https://ieeexplore.ieee.org/document/8117566'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

There have been many traffic balancing solutions for datacenter networks. All of them require modifications to the network fabric or/and virtual machines. In this paper, we propose Virtual Multi-channel Scatter (VMS), a new traffic balancing solution in datacenter networks. VMS works in the virtual switches between the network fabric and virtual machines. It can be deployed by datacenter operators at a relatively low cost without extra restrictions to virtual machine users. VMS scatters packets in one TCP flow to several different forwarding paths. It employs an adaptive path selection based on the virtual window size of different paths. We implemented VMS based on OVS. Our evaluation demonstrates that VMS improves traffic balancing very well, and the performance of VMS is approximate to MPTCP in almost all the cases, while only modifies virtual switches. Further, the overhead of VMS is tolerable.

[Download](https://ieeexplore.ieee.org/document/8117566)

