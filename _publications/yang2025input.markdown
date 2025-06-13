---
layout: publication
title: 'DASH: Input-aware Dynamic Layer Skipping For Efficient LLM Inference With Markov Decision Policies'
authors: Ning Yang, Fangxin Liu, Junjie Wang, Tao Yang, Kan Liu, Haibing Guan, Li Jiang
conference: "Arxiv"
year: 2025
bibkey: yang2025input
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.17420'}
tags: ['Reinforcement Learning', 'Model Architecture', 'Tools']
---
Large language models (LLMs) have achieved remarkable performance across a wide range of NLP tasks. However, their substantial inference cost poses a major barrier to real-world deployment, especially in latency-sensitive scenarios. To address this challenge, we propose \textbf\{DASH\}, an adaptive layer-skipping framework that dynamically selects computation paths conditioned on input characteristics. We model the skipping process as a Markov Decision Process (MDP), enabling fine-grained token-level decisions based on intermediate representations. To mitigate potential performance degradation caused by skipping, we introduce a lightweight compensation mechanism that injects differential rewards into the decision process. Furthermore, we design an asynchronous execution strategy that overlaps layer computation with policy evaluation to minimize runtime overhead. Experiments on multiple LLM architectures and NLP benchmarks show that our method achieves significant inference acceleration while maintaining competitive task performance, outperforming existing methods.
