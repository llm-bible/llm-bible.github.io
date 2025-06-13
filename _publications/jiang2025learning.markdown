---
layout: publication
title: 'Learning To Rank Chain-of-thought: An Energy-based Approach With Outcome Supervision'
authors: Eric Hanchen Jiang, Haozheng Luo, Shengyuan Pang, Xiaomin Li, Zhenting Qi, Hengli Li, Cheng-fu Yang, Zongyu Lin, Xinfeng Li, Hao Xu, Kai-wei Chang, Ying Nian Wu
conference: "Arxiv"
year: 2025
bibkey: jiang2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14999'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting', 'Training Techniques']
---
Mathematical reasoning presents a significant challenge for Large Language Models (LLMs), often requiring robust multi step logical consistency. While Chain of Thought (CoT) prompting elicits reasoning steps, it doesn't guarantee correctness, and improving reliability via extensive sampling is computationally costly. This paper introduces the Energy Outcome Reward Model (EORM), an effective, lightweight, post hoc verifier. EORM leverages Energy Based Models (EBMs) to simplify the training of reward models by learning to assign a scalar energy score to CoT solutions using only outcome labels, thereby avoiding detailed annotations. It achieves this by interpreting discriminator output logits as negative energies, effectively ranking candidates where lower energy is assigned to solutions leading to correct final outcomes implicitly favoring coherent reasoning. On mathematical benchmarks (GSM8k, MATH), EORM significantly improves final answer accuracy (e.g., with Llama 3 8B, achieving 90.7% on GSM8k and 63.7% on MATH). EORM effectively leverages a given pool of candidate solutions to match or exceed the performance of brute force sampling, thereby enhancing LLM reasoning outcome reliability through its streamlined post hoc verification process.
