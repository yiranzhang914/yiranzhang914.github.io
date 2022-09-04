---
title: "Congestion Detection in Lossless Networks"
collection: publications
permalink: /publication/tcd-sigcomm
excerpt: "Yiran Zhang, Yifan Liu, Qingkai Meng, Fengyuan Ren"
date: 2021-08-23
venue: 'SIGCOMM (**Top 1 conference in computer networks**)'
paperurl: 'https://dl.acm.org/doi/10.1145/3452296.3472899'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Congestion detection is the cornerstone of end-to-end congestion control. Through in-depth observations and understandings, we reveal that existing congestion detection mechanisms in mainstream lossless networks (i.e., Converged Enhanced Ethernet and InfiniBand) are improper, due to failing to cognize the interaction between hop-by-hop flow controls and congestion detection behaviors in switches. We define ternary states of switch ports and present Ternary Congestion Detection (TCD) for mainstream lossless networks. Testbed and extensive simulations demonstrate that TCD can detect congestion ports accurately and identify flows contributing to congestion as well as flows only affected by hop-by-hop flow controls. Meanwhile, we shed light on how to incorporate TCD with rate control. Case studies show that existing congestion control algorithms can achieve 3.3x and 2.0x better median and 99th-percentile FCT slowdown by combining with TCD.

[Download](https://dl.acm.org/doi/10.1145/3452296.3472899)  
[Public Review](https://dl.acm.org/action/downloadSupplement?doi=10.1145%2F3452296.3472899&file=121-public-review.pdf)

