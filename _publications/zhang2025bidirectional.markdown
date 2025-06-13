---
layout: publication
title: 'Bidirectional Lms Are Better Knowledge Memorizers? A Benchmark For Real-world Knowledge Injection'
authors: Yuwei Zhang, Wenhao Yu, Shangbin Feng, Yifan Zhu, Letian Peng, Jayanth Srinivasa, Gaowen Liu, Jingbo Shang
conference: "Arxiv"
year: 2025
bibkey: zhang2025bidirectional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12306"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Prompting', 'Pre-Training']
---
Despite significant advances in large language models (LLMs), their knowledge memorization capabilities remain underexplored, due to the lack of standardized and high-quality test ground. In this paper, we introduce a novel, real-world and large-scale knowledge injection benchmark that evolves continuously over time without requiring human intervention. Specifically, we propose WikiDYK, which leverages recently-added and human-written facts from Wikipedia's "Did You Know..." entries. These entries are carefully selected by expert Wikipedia editors based on criteria such as verifiability and clarity. Each entry is converted into multiple question-answer pairs spanning diverse task formats from easy cloze prompts to complex multi-hop questions. WikiDYK contains 12,290 facts and 77,180 questions, which is also seamlessly extensible with future updates from Wikipedia editors. Extensive experiments using continued pre-training reveal a surprising insight: despite their prevalence in modern LLMs, Causal Language Models (CLMs) demonstrate significantly weaker knowledge memorization capabilities compared to Bidirectional Language Models (BiLMs), exhibiting a 23% lower accuracy in terms of reliability. To compensate for the smaller scales of current BiLMs, we introduce a modular collaborative framework utilizing ensembles of BiLMs as external knowledge repositories to integrate with LLMs. Experiment shows that our framework further improves the reliability accuracy by up to 29.1%.
