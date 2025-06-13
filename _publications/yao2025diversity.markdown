---
layout: publication
title: 'Diversity-aware Policy Optimization For Large Language Model Reasoning'
authors: Jian Yao, Ran Cheng, Xingyu Wu, Jibin Wu, Kay Chen Tan
conference: "Arxiv"
year: 2025
bibkey: yao2025diversity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23433"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
The reasoning capabilities of large language models (LLMs) have advanced rapidly, particularly following the release of DeepSeek R1, which has inspired a surge of research into data quality and reinforcement learning (RL) algorithms. Despite the pivotal role diversity plays in RL, its influence on LLM reasoning remains largely underexplored. To bridge this gap, this work presents a systematic investigation into the impact of diversity in RL-based training for LLM reasoning, and proposes a novel diversity-aware policy optimization method. Across evaluations on 12 LLMs, we observe a strong positive correlation between the solution diversity and Potential at k (a novel metric quantifying an LLM's reasoning potential) in high-performing models. This finding motivates our method to explicitly promote diversity during RL training. Specifically, we design a token-level diversity and reformulate it into a practical objective, then we selectively apply it to positive samples. Integrated into the R1-zero training framework, our method achieves a 3.5 percent average improvement across four mathematical reasoning benchmarks, while generating more diverse and robust solutions.
