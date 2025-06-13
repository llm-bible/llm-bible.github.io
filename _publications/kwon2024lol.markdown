---
layout: publication
title: 'Lol-pim: Long-context LLM Decoding With Scalable DRAM-PIM System'
authors: Hyucksung Kwon, Kyungmo Koo, Janghyeon Kim, Woongkyu Lee, Minjae Lee, Hyungdeok Lee, Yousub Jung, Jaehan Park, Yosub Song, Byeongsu Yang, Haerang Choi, Guhyun Kim, Jongsoon Won, Woojae Shin, Changhyun Kim, Gyeongcheol Shin, Yongkee Kwon, Ilkon Kim, Euicheol Lim, John Kim, Jungwook Choi
conference: "Arxiv"
year: 2024
bibkey: kwon2024lol
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20166"}
tags: ['Model Architecture', 'Applications', 'Attention Mechanism', 'Reinforcement Learning']
---
The expansion of large language models (LLMs) with hundreds of billions of
parameters presents significant challenges to computational resources,
particularly data movement and memory bandwidth. Long-context LLMs, which
process sequences of tens of thousands of tokens, further increase the demand
on the memory system as the complexity in attention layers and key-value cache
sizes is proportional to the context length. Processing-in-Memory (PIM)
maximizes memory bandwidth by moving compute to the data and can address the
memory bandwidth challenges; however, PIM is not necessarily scalable to
accelerate long-context LLM because of limited per-module memory capacity and
the inflexibility of fixed-functional unit PIM architecture and static memory
management. In this work, we propose LoL-PIM which is a multi-node PIM
architecture that accelerates long context LLM through hardware-software
co-design. In particular, we propose how pipeline parallelism can be exploited
across a multi-PIM module while a direct PIM access (DPA) controller (or DMA
for PIM) is proposed that enables dynamic PIM memory management and results in
efficient PIM utilization across a diverse range of context length. We
developed an MLIR-based compiler for LoL-PIM extending a commercial PIM-based
compiler where the software modifications were implemented and evaluated, while
the hardware changes were modeled in the simulator. Our evaluations demonstrate
that LoL-PIM significantly improves throughput and reduces latency for
long-context LLM inference, outperforming both multi-GPU and GPU-PIM systems
(up to 8.54x and 16.0x speedup, respectively), thereby enabling more efficient
deployment of LLMs in real-world applications.
