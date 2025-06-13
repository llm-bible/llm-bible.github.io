---
layout: publication
title: 'Accelerating RL For LLM Reasoning With Optimal Advantage Regression'
authors: Kianté Brantley, Mingyu Chen, Zhaolin Gao, Jason D. Lee, Wen Sun, Wenhao Zhan, Xuezhou Zhang
conference: "Arxiv"
year: 2025
bibkey: brantley2025accelerating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20686'}
  - {name: "Code", url: 'https://github.com/ZhaolinGao/A-PO'}
tags: ['Agentic', 'Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Reinforcement learning (RL) has emerged as a powerful tool for fine-tuning large language models (LLMs) to improve complex reasoning abilities. However, state-of-the-art policy optimization methods often suffer from high computational overhead and memory consumption, primarily due to the need for multiple generations per prompt and the reliance on critic networks or advantage estimates of the current policy. In this paper, we propose \\(A\\)*-PO, a novel two-stage policy optimization framework that directly approximates the optimal advantage function and enables efficient training of LLMs for reasoning tasks. In the first stage, we leverage offline sampling from a reference policy to estimate the optimal value function \\(V\\)*, eliminating the need for costly online value estimation. In the second stage, we perform on-policy updates using a simple least-squares regression loss with only a single generation per prompt. Theoretically, we establish performance guarantees and prove that the KL-regularized RL objective can be optimized without requiring complex exploration strategies. Empirically, \\(A\\)*-PO achieves competitive performance across a wide range of mathematical reasoning benchmarks, while reducing training time by up to 2\\(\times\\) and peak memory usage by over 30% compared to PPO, GRPO, and REBEL. Implementation of \\(A\\)*-PO can be found at https://github.com/ZhaolinGao/A-PO.
