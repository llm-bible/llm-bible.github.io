---
layout: publication
title: 'Inner Thinking Transformer: Leveraging Dynamic Depth Scaling To Foster Adaptive Internal Thinking'
authors: Yilong Chen, Junyuan Shang, Zhenyu Zhang, Yanxi Xie, Jiawei Sheng, Tingwen Liu, Shuohuan Wang, Yu Sun, Hua Wu, Haifeng Wang
conference: "Arxiv"
year: 2025
bibkey: chen2025inner
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13842'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) face inherent performance bottlenecks under
parameter constraints, particularly in processing critical tokens that demand
complex reasoning. Empirical analysis reveals challenging tokens induce abrupt
gradient spikes across layers, exposing architectural stress points in standard
Transformers. Building on this insight, we propose Inner Thinking Transformer
(ITT), which reimagines layer computations as implicit thinking steps. ITT
dynamically allocates computation through Adaptive Token Routing, iteratively
refines representations via Residual Thinking Connections, and distinguishes
reasoning phases using Thinking Step Encoding. ITT enables deeper processing of
critical tokens without parameter expansion. Evaluations across 162M-466M
parameter models show ITT achieves 96.5% performance of a 466M Transformer
using only 162M parameters, reduces training data by 43.2%, and outperforms
Transformer/Loop variants in 11 benchmarks. By enabling elastic computation
allocation during inference, ITT balances performance and efficiency through
architecture-aware optimization of implicit thinking pathways.
