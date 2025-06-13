---
layout: publication
title: 'Treat Visual Tokens As Text? But Your MLLM Only Needs Fewer Efforts To See'
authors: Zeliang Zhang, Phu Pham, Wentian Zhao, Kun Wan, Yu-jhe Li, Jianing Zhou, Daniel Miranda, Ajinkya Kale, Chenliang Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024treat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06169"}
tags: ['Multimodal Models', 'Model Architecture', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Pruning', 'Attention Mechanism']
---
By treating visual tokens from visual encoders as text tokens, Multimodal
Large Language Models (MLLMs) have achieved remarkable progress across diverse
visual understanding tasks, leveraging the robust architectures of Large
Language Models (LLMs). However, as token counts grow, the quadratic scaling of
computation in LLMs introduces a significant efficiency bottleneck, impeding
further scalability. Although recent approaches have explored pruning visual
tokens or employing lighter LLM architectures, the computational overhead from
an increasing number of visual tokens remains a substantial challenge.
  In this study, we investigate the redundancy in visual computation at both
the parameter and computational pattern levels within LLaVA, a representative
MLLM, and introduce a suite of streamlined strategies to enhance efficiency.
These include neighbor-aware visual token attention, pruning of inactive visual
attention heads, and selective layer dropping for visual computations. By
implementing these strategies in LLaVA, we achieve a reduction in computational
demands of 88% while maintaining model performance across key benchmarks.
Additionally, we validate the existence of visual computational redundancy in
other MLLMs, such as Qwen2-VL-7B and InternVL-2.0-4B/8B/26B. These results
present a novel pathway for MLLMs to handle dense visual tokens with minimal
computational costs. Code and model checkpoints will be released to support
further research.
