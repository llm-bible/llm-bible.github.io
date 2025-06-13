---
layout: publication
title: 'Rag-rewardbench: Benchmarking Reward Models In Retrieval Augmented Generation For Preference Alignment'
authors: Zhuoran Jin, Hongbang Yuan, Tianyi Men, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao
conference: "Arxiv"
year: 2024
bibkey: jin2024rag
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.13746'}
  - {name: "Code", url: 'https://huggingface.co/datasets/jinzhuoran/RAG-RewardBench/'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Reinforcement Learning']
---
Despite the significant progress made by existing retrieval augmented
language models (RALMs) in providing trustworthy responses and grounding in
reliable sources, they often overlook effective alignment with human
preferences. In the alignment process, reward models (RMs) act as a crucial
proxy for human values to guide optimization. However, it remains unclear how
to evaluate and select a reliable RM for preference alignment in RALMs. To this
end, we propose RAG-RewardBench, the first benchmark for evaluating RMs in RAG
settings. First, we design four crucial and challenging RAG-specific scenarios
to assess RMs, including multi-hop reasoning, fine-grained citation,
appropriate abstain, and conflict robustness. Then, we incorporate 18 RAG
subsets, six retrievers, and 24 RALMs to increase the diversity of data
sources. Finally, we adopt an LLM-as-a-judge approach to improve preference
annotation efficiency and effectiveness, exhibiting a strong correlation with
human annotations. Based on the RAG-RewardBench, we conduct a comprehensive
evaluation of 45 RMs and uncover their limitations in RAG scenarios.
Additionally, we also reveal that existing trained RALMs show almost no
improvement in preference alignment, highlighting the need for a shift towards
preference-aligned training.We release our benchmark and code publicly at
https://huggingface.co/datasets/jinzhuoran/RAG-RewardBench/ for future work.
