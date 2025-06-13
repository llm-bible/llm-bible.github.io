---
layout: publication
title: 'Edgemoe: Empowering Sparse Large Language Models On Mobile Devices'
authors: Rongjie Yi, Liwei Guo, Shiyun Wei, Ao Zhou, Shangguang Wang, Mengwei Xu
conference: "Arxiv"
year: 2023
bibkey: yi2023empowering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.14352'}
  - {name: "Code", url: 'https://github.com/UbiquitousLearning/mllm'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'GPT', 'Model Architecture']
---
Large language models (LLMs) such as GPTs and Mixtral-8x7B have
revolutionized machine intelligence due to their exceptional abilities in
generic ML tasks. Transiting LLMs from datacenters to edge devices brings
benefits like better privacy and availability, but is challenged by their
massive parameter size and thus unbearable runtime costs. To this end, we
present EdgeMoE, an on-device inference engine for mixture-of-expert (MoE) LLMs
-- a popular form of sparse LLM that scales its parameter size with almost
constant computing complexity. EdgeMoE achieves both memory- and
compute-efficiency by partitioning the model into the storage hierarchy:
non-expert weights are held in device memory; while expert weights are held on
external storage and fetched to memory only when activated. This design is
motivated by a key observation that expert weights are bulky but infrequently
used due to sparse activation. To further reduce the expert I/O swapping
overhead, EdgeMoE incorporates two novel techniques: (1) expert-wise bitwidth
adaptation that reduces the expert sizes with tolerable accuracy loss; (2)
expert preloading that predicts the activated experts ahead of time and
preloads it with the compute-I/O pipeline. On popular MoE LLMs and edge
devices, EdgeMoE showcase significant memory savings and speedup over
competitive baselines. The code is available at
https://github.com/UbiquitousLearning/mllm.
