---
layout: publication
title: 'Unlocking Large Language Model''s Planning Capabilities With Maximum Diversity Fine-tuning'
authors: Wenjun Li, Changyu Chen, Pradeep Varakantham
conference: "Arxiv"
year: 2024
bibkey: li2024unlocking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.10479'}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated impressive task-solving
capabilities through prompting techniques and system designs, including solving
planning tasks (e.g., math proofs, basic travel planning) when sufficient data
is available online and used during pre-training. However, for planning tasks
with limited prior data (e.g., blocks world, advanced travel planning), the
performance of LLMs, including proprietary models like GPT and Gemini, is poor.
This paper investigates the impact of fine-tuning on the planning capabilities
of LLMs, revealing that LLMs can achieve strong performance in planning through
substantial (tens of thousands of specific examples) fine-tuning. Yet, this
process incurs high economic, time, and computational costs for each planning
problem variation. To address this, we propose Clustering-Based Maximum
Diversity Sampling (CMDS), which selects diverse and representative data to
enhance sample efficiency and the model's generalization capability. Extensive
evaluations demonstrate that CMDS-l, a baseline method combining CMDS with
language embeddings, outperforms random sampling. Furthermore, we introduce a
novel algorithm, CMDS-g, which encodes planning task instances with their graph
representations into the embedding space. Empirical results show that CMDS-g
consistently outperforms baseline methods across various scales and multiple
benchmark domains.
