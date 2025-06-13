---
layout: publication
title: 'From Token To Action: State Machine Reasoning To Mitigate Overthinking In Information Retrieval'
authors: Dohyeon Lee, Yeonseok Jeong, Seung-won Hwang
conference: "Arxiv"
year: 2025
bibkey: lee2025from
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23059"}
  - {name: "Code", url: "https://github.com/ldilab/SMR"}
tags: ['Tools', 'Applications', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Chain-of-Thought (CoT) prompting enables complex reasoning in large language models (LLMs), including applications in information retrieval (IR). However, it often leads to overthinking, where models produce excessively long and semantically redundant traces with little or no benefit. We identify two key challenges in IR: redundant trajectories that revisit similar states and misguided reasoning that diverges from user intent. To address these, we propose State Machine Reasoning (SMR), a transition-based reasoning framework composed of discrete actions (Refine, Rerank, Stop) that support early stopping and fine-grained control. Experiments on the BEIR and BRIGHT benchmarks show that SMR improves retrieval performance (nDCG@10) by 3.4% while reducing token usage by 74.4%. It generalizes across LLMs and retrievers without requiring task-specific tuning, offering a practical alternative to conventional CoT reasoning. The code and details are available at https://github.com/ldilab/SMR.
