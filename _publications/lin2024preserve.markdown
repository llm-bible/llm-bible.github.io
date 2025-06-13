---
layout: publication
title: 'To Preserve Or To Compress: An In-depth Study Of Connector Selection In Multimodal Large Language Models'
authors: Junyan Lin, Haoran Chen, Dawei Zhu, Xiaoyu Shen
conference: "Arxiv"
year: 2024
bibkey: lin2024preserve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06765"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Multimodal Models']
---
In recent years, multimodal large language models (MLLMs) have garnered
significant attention from both industry and academia. However, there is still
considerable debate on constructing MLLM architectures, particularly regarding
the selection of appropriate connectors for perception tasks of varying
granularities. This paper systematically investigates the impact of connectors
on MLLM performance. Specifically, we classify connectors into
feature-preserving and feature-compressing types. Utilizing a unified
classification standard, we categorize sub-tasks from three comprehensive
benchmarks, MMBench, MME, and SEED-Bench, into three task types: coarse-grained
perception, fine-grained perception, and reasoning, and evaluate the
performance. Our findings reveal that feature-preserving connectors excel in
*fine-grained perception* tasks due to their ability to retain detailed
visual information. In contrast, feature-compressing connectors, while less
effective in fine-grained perception tasks, offer significant speed advantages
and perform comparably in *coarse-grained perception* and *reasoning*
tasks. These insights are crucial for guiding MLLM architecture design and
advancing the optimization of MLLM architectures.
