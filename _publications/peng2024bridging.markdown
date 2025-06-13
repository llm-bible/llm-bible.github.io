---
layout: publication
title: 'Multimath: Bridging Visual And Mathematical Reasoning For Large Language Models'
authors: Shuai Peng, Di Fu, Liangcai Gao, Xiuqin Zhong, Hongguang Fu, Zhi Tang
conference: "Arxiv"
year: 2024
bibkey: peng2024bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.00147'}
  - {name: "Code", url: 'https://github.com/pengshuai-rin/MultiMath'}
tags: ['Agentic', 'Has Code', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning']
---
The rapid development of large language models (LLMs) has spurred extensive
research into their domain-specific capabilities, particularly mathematical
reasoning. However, most open-source LLMs focus solely on mathematical
reasoning, neglecting the integration with visual injection, despite the fact
that many mathematical tasks rely on visual inputs such as geometric diagrams,
charts, and function plots. To fill this gap, we introduce
\textbf\{MultiMath-7B\}, a multimodal large language model that bridges the gap
between math and vision. \textbf\{MultiMath-7B\} is trained through a four-stage
process, focusing on vision-language alignment, visual and math
instruction-tuning, and process-supervised reinforcement learning. We also
construct a novel, diverse and comprehensive multimodal mathematical dataset,
\textbf\{MultiMath-300K\}, which spans K-12 levels with image captions and
step-wise solutions. MultiMath-7B achieves state-of-the-art (SOTA) performance
among open-source models on existing multimodal mathematical benchmarks and
also excels on text-only mathematical benchmarks. Our model and dataset are
available at
\{\textcolor\{blue\}\{\url\{https://github.com/pengshuai-rin/MultiMath\}\}\}.
