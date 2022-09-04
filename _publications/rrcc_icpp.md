---
title: "Receiver-Driven Congestion Control for InfiniBand"
collection: publications
permalink: /publication/rrcc-icpp
excerpt: 'Yiran Zhang, Kun Qian, Fengyuan Ren'
date: 2021-08-30
venue: 'Proceedings of the 50th International Conference on Parallel Processing (ICPP)'
paperurl: 'https://dl.acm.org/doi/fullHtml/10.1145/3472456.3472466'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---


InfiniBand (IB) has become one of the most popular high-speed interconnects in High Performance Computing (HPC). The backpressure effect of credit-based link-layer flow control in IB introduces congestion spreading, which increases queueing delay and hurts application completion time. IB congestion control (IB CC) has been defined in IB specification to address the congestion spreading problem. Nowadays, HPC clusters are increasingly being used to run diverse workloads with a shared network infrastructure. The coexistence of messages transfers of different applications imposes great challenges to IB CC. In this paper, we re-exam IB CC through fine-grained experimental observations and reveal several fundamental problems. Inspired by our understanding and insights, we present a new receiver-driven congestion control for InfiniBand (RR CC). RR CC includes two key mechanisms: receiver-driven congestion identification and receiver-driven rate regulation, which empower eliminating both in-network congestion and endpoint congestion in one control loop. RR CC has much fewer parameters and requires no modifications to InfiniBand switches. Evaluations show that RR CC achieves better average/tail message latency and link utilization than IB CC under various scenarios.

[Download](https://dl.acm.org/doi/fullHtml/10.1145/3472456.3472466)

