---
layout: publication
title: 'Training Small Reasoning Llms With Cognitive Preference Alignment'
authors: Wenrui Cai, Chengyu Wang, Junbing Yan, Jun Huang, Xiangzhong Fang
conference: "Arxiv"
year: 2025
bibkey: cai2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09802'}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools']
---
The reasoning capabilities of large language models (LLMs), such as OpenAI's
o1 and DeepSeek-R1, have seen substantial advancements through deep thinking.
However, these enhancements come with significant resource demands,
underscoring the need to explore strategies to train effective reasoning LLMs
with far fewer parameters. A critical challenge is that smaller models have
different capacities and cognitive trajectories than their larger counterparts.
Hence, direct distillation of chain-of-thought (CoT) results from large LLMs to
smaller ones can be sometimes ineffective and requires a huge amount of
annotated data. In this paper, we introduce a novel framework called
Critique-Rethink-Verify (CRV), designed for training smaller yet powerful
reasoning LLMs. Our CRV framework consists of multiple LLM agents, each
specializing in unique abilities: (i) critiquing the CoTs according to the
cognitive capabilities of smaller models, (ii) rethinking and refining these
CoTs based on the critiques, and (iii) verifying the correctness of the refined
results. We further propose the cognitive preference optimization (CogPO)
algorithm to enhance the reasoning abilities of smaller models by aligning
thoughts of these models with their cognitive capacities. Comprehensive
evaluations on challenging reasoning benchmarks demonstrate the efficacy of CRV
and CogPO, which outperforms other training methods by a large margin.
