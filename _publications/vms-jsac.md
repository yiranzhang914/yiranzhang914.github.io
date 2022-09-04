---
title: "VMS: Load Balancing Based on the Virtual Switch Layer in Datacenter Networks"
collection: publications
permalink: /publication/vms-jsac
excerpt: 'Yiran Zhang, Jun Bi, Zhaogeng Li, Yu Zhou, Yangyang Wang'
date: 2020-06-30
venue: 'IEEE JSAC (Journal on Selected Areas in Communications)'
paperurl: 'https://ieeexplore.ieee.org/document/9060887'
#citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---


There have been many load balancing solutions for datacenter networks. Almost all of them require modifications to the network fabric or/and virtual machines. Recently, the virtual switch layer becomes an ideal location for datacenter operators to deal with the load balancing problem. In this paper, we propose Virtual Multi-channel Scatter (VMS), a packet-level load balancing design in the virtual switch layer. VMS scatters packets in one TCP flow to several different forwarding paths (channels). VMS has several noteworthy properties. First, VMS is low cost and transparent to tenants. It can be deployed when the datacenter operators do not attempt to change the network fabric or cannot control the transport protocol inside VMs. Second, by employing window-based channel selection, VMS is adaptive to network congestion and topology asymmetry. Third, VMS works well with Generic Segmentation Offload/Generic Receive Offload (GRO/GSO) mechanism in the Linux kernel, unlike other packet-level load balancing schemes. Finally, VMS can also be offloaded to SmartNIC to reduce CPU overhead further. Our evaluations show that VMS achieves comparable performance to the ideal packet-level scheme in normal cases and well handles topology asymmetries, while only modifies the virtual switch layer. In the symmetric topology, VMS achieves up to 47% and 22% better flow completion time (FCT) than Equal Cost MultiPath (ECMP) and the best-of-breed flowlet-level CONGA. When there is topology asymmetry, VMS outperforms the ideal packet-level scheme and CONGA by up to 3.0\times and 1.4\times respectively. Further, the overhead of VMS is tolerable.

[Download paper here](https://ieeexplore.ieee.org/document/9060887)

