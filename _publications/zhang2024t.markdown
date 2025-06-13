---
layout: publication
title: 'T-REX: Mixture-of-rank-one-experts With Semantic-aware Intuition For Multi-task Large Language Model Finetuning'
authors: Rongyu Zhang, Yijiang Liu, Huanrui Yang, Shenli Zheng, Dan Wang, Yuan Du, Li Du, Shanghang Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024t
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08985"}
  - {name: "Code", url: "https://github.com/RoyZry98/T-REX-Pytorch}{Code"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Has Code']
---
Large language models (LLMs) encounter significant adaptation challenges in diverse multitask finetuning. Mixture-of-experts (MoE) provides a promising solution with a dynamic architecture, enabling effective task decoupling. However, scaling up the number of MoE experts incurs substantial parameter and computational overheads and suffers from limited performance gain due to naive routing mechanisms. In this paper, we design a novel framework, mix\underline\{\textbf\{T\}\}ure\underline\{\textbf\{-\}\}of-\underline\{\textbf\{R\}\}ank-on\underline\{\textbf\{E\}\}-e\underline\{\textbf\{X\}\}perts (\texttt\{T-REX\}), which leverages the combination of ultra-low rank experts to construct LoRA weights on pretrained LLMs. The rank-1 experts enable a mix-and-match mechanism to quadratically expand the vector subspace of experts with linear parameter overheads, achieving approximate error reduction with optimal efficiency. In addition, T-REX offers implicit guidance to the router, leveraging the inherent semantic clustering of training embeddings as prior knowledge, enabling optimized feature allocation across experts for a smoother convergence. Extensive theoretical and empirical results demonstrate that T-REX achieves superior efficiency and generalizability across diverse tasks. Compared with other LoRA-based methods, T-REX achieves up to 1.78% mean accuracy improvement with around 30%-40% less trainable parameters across 14 public datasets. \href\{https://github.com/RoyZry98/T-REX-Pytorch\}\{Code\} is available.
