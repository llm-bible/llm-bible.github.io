---
layout: publication
title: 'L3: DIMM-PIM Integrated Architecture And Coordination For Scalable Long-context LLM Inference'
authors: Qingyuan Liu, Liyan Chen, Yanning Yang, Haocheng Wang, Dong Du, Zhigang Mao, Naifeng Jing, Yubin Xia, Haibo Chen
conference: "Arxiv"
year: 2025
bibkey: liu2025dimm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17584"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Reinforcement Learning']
---
Large Language Models (LLMs) increasingly require processing long text
sequences, but GPU memory limitations force difficult trade-offs between memory
capacity and bandwidth. While HBM-based acceleration offers high bandwidth, its
capacity remains constrained. Offloading data to host-side DIMMs improves
capacity but introduces costly data swapping overhead. We identify that the
critical memory bottleneck lies in the decoding phase of multi-head attention
(MHA) exclusively, which demands substantial capacity for storing KV caches and
high bandwidth for attention computation. Our key insight reveals this
operation uniquely aligns with modern DIMM-based processing-in-memory (PIM)
architectures, which offers scalability of both capacity and bandwidth.
  Based on this observation and insight, we propose L3, a hardware-software
co-designed system integrating DIMM-PIM and GPU devices. L3 introduces three
innovations: First, hardware redesigns resolve data layout mismatches and
computational element mismatches in DIMM-PIM, enhancing LLM inference
utilization. Second, communication optimization enables hiding the data
transfer overhead with the computation. Third, an adaptive scheduler
coordinates GPU-DIMM-PIM operations to maximize parallelism between devices.
Evaluations using real-world traces show L3 achieves up to 6.1\\(\times\\) speedup
over state-of-the-art HBM-PIM solutions while significantly improving batch
sizes.
