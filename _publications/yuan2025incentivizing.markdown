---
layout: publication
title: 'Incentivizing Strong Reasoning From Weak Supervision'
authors: Yige Yuan, Teng Xiao, Shuchang Tao, Xue Wang, Jinyang Gao, Bolin Ding, Bingbing Xu
conference: "Arxiv"
year: 2025
bibkey: yuan2025incentivizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20072"}
  - {name: "Code", url: "https://github.com/yuanyige/w2sr"}
tags: ['Fine-Tuning', 'Agentic', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated impressive performance on reasoning-intensive tasks, but enhancing their reasoning abilities typically relies on either reinforcement learning (RL) with verifiable signals or supervised fine-tuning (SFT) with high-quality long chain-of-thought (CoT) demonstrations, both of which are expensive. In this paper, we study a novel problem of incentivizing the reasoning capacity of LLMs without expensive high-quality demonstrations and reinforcement learning. We investigate whether the reasoning capabilities of LLMs can be effectively incentivized via supervision from significantly weaker models. We further analyze when and why such weak supervision succeeds in eliciting reasoning abilities in stronger models. Our findings show that supervision from significantly weaker reasoners can substantially improve student reasoning performance, recovering close to 94% of the gains of expensive RL at a fraction of the cost. Experiments across diverse benchmarks and model architectures demonstrate that weak reasoners can effectively incentivize reasoning in stronger student models, consistently improving performance across a wide range of reasoning tasks. Our results suggest that this simple weak-to-strong paradigm is a promising and generalizable alternative to costly methods for incentivizing strong reasoning capabilities at inference-time in LLMs. The code is publicly available at https://github.com/yuanyige/w2sr.
