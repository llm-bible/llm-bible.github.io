---
layout: publication
title: 'Condor: Enhance LLM Alignment With Knowledge-driven Data Synthesis And Refinement'
authors: Maosong Cao, Taolin Zhang, Mo Li, Chuyu Zhang, Yunxin Liu, Haodong Duan, Songyang Zhang, Kai Chen
conference: "Arxiv"
year: 2025
bibkey: cao2025enhance
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.12273'}
tags: ['Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The quality of Supervised Fine-Tuning (SFT) data plays a critical role in
enhancing the conversational capabilities of Large Language Models (LLMs).
However, as LLMs become more advanced, the availability of high-quality
human-annotated SFT data has become a significant bottleneck, necessitating a
greater reliance on synthetic training data. In this work, we introduce Condor,
a novel two-stage synthetic data generation framework that incorporates World
Knowledge Tree and Self-Reflection Refinement to produce high-quality SFT data
at scale. Our experimental results demonstrate that a base model fine-tuned on
only 20K Condor-generated samples achieves superior performance compared to
counterparts. The additional refinement stage in Condor further enables
iterative self-improvement for LLMs at various scales (up to 72B), validating
the effectiveness of our approach. Furthermore, our investigation into the
scaling for synthetic data in post-training reveals substantial unexplored
potential for performance improvements, opening promising avenues for future
research.
