---
title: "CrossDBT: An LLVM-based User-level Dynamic Binary Translation Emulator (**Awarded Best Paper**)"
collection: publications
permalink: /publication/crossDBT-europar
excerpt: 'Wei Li, Xiaohui Luo, Yiran Zhang, Qingkai Meng and Fengyuan Ren'
date: 2022-08-22
venue: 'International European Conference on Parallel and Distributed Computing (Euro-Par)'
paperurl: 'https://dl.acm.org/doi/abs/10.1007/978-3-031-12597-3_1'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Emulation of Instruction Set Architecture (ISA) is necessary for a wide variety of use cases, such as providing the compatibility to execute programs compiled for a different ISA. This issue is usually solved using Dynamic Binary Translation (DBT), where guest machine code is translated to host ISA on runtime and Just-in-time (JIT) compilation is performed to achieve high-performance emulation. QEMU, a famous emulator, is developed to solve this issue, where Tiny Code Generator (TCG) is constructed to translate guest binary code to TCG Intermediate Representation (IR), and then generate target ISA machine code from TCG IR. Due to the limitations of TCG, some extensions, such as HQEMU, use LLVM as the backend to optimize programs and generate high-performance machine code. However, HQEMU is limited by its underlying implementation. That is, HQEMU still translates guest binary code to TCG IR at first. In this paper, we develop a novel, LLVM-based emulator, where guest machine code is directly lifted to LLVM IR to reduce the extra overhead and produce high-quality machine code. We evaluate our DBT emulator using BYTEmark benchmark and demonstrating its ability to outperform the de facto standard QEMU DBT system. The evaluation results confirm that our emulator delivers an average speedup of 3.3x over QEMU across BYTEmark benchmark compiled for x86-64 running on an ARMv8 platform, meanwhile, demonstrate that our user-level DBT emulator can significantly reduce the overhead to run a program on a cross-ISA system.

[Download paper here](https://dl.acm.org/doi/abs/10.1007/978-3-031-12597-3_1)

