---
layout: publication
title: 'Codepmp: Scalable Preference Model Pretraining For Large Language Model Reasoning'
authors: Huimu Yu, Xing Wu, Haotian Xu, Debing Zhang, Songlin Hu
conference: "Arxiv"
year: 2024
bibkey: yu2024scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02229"}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have made significant progress in natural language understanding and generation, driven by scalable pretraining and advanced finetuning. However, enhancing reasoning abilities in LLMs, particularly via reinforcement learning from human feedback (RLHF), remains challenging due to the scarcity of high-quality preference data, which is labor-intensive to annotate and crucial for reward model (RM) finetuning. To alleviate this issue, we introduce CodePMP, a scalable preference model pretraining (PMP) pipeline that utilizes a large corpus of synthesized code-preference pairs from publicly available high-quality source code. CodePMP improves RM finetuning efficiency by pretraining preference models on large-scale synthesized code-preference pairs. We evaluate CodePMP on mathematical reasoning tasks (GSM8K, MATH) and logical reasoning tasks (ReClor, LogiQA2.0), consistently showing significant improvements in reasoning performance of LLMs and highlighting the importance of scalable preference model pretraining for efficient reward modeling.
