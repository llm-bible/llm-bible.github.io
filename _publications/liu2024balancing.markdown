---
layout: publication
title: 'Balancing Accuracy And Efficiency In Multi-turn Intent Classification For Llm-powered Dialog Systems In Production'
authors: Junhua Liu, Yong Keat Tan, Bin Fu, Kwan Hui Lim
conference: "Arxiv"
year: 2024
bibkey: liu2024balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.12307"}
tags: ['RAG', 'Applications', 'Efficiency and Optimization', 'Tools']
---
Accurate multi-turn intent classification is essential for advancing
conversational AI systems. However, challenges such as the scarcity of
comprehensive datasets and the complexity of contextual dependencies across
dialogue turns hinder progress. This paper presents two novel approaches
leveraging Large Language Models (LLMs) to enhance scalability and reduce
latency in production dialogue systems. First, we introduce Symbol Tuning,
which simplifies intent labels to reduce task complexity and improve
performance in multi-turn dialogues. Second, we propose C-LARA
(Consistency-aware, Linguistics Adaptive Retrieval Augmentation), a framework
that employs LLMs for data augmentation and pseudo-labeling to generate
synthetic multi-turn dialogues. These enriched datasets are used to fine-tune a
small, efficient model suitable for deployment. Experiments conducted on
multilingual dialogue datasets demonstrate significant improvements in
classification accuracy and resource efficiency. Our methods enhance multi-turn
intent classification accuracy by 5.09%, reduce annotation costs by 40%, and
enable scalable deployment in low-resource multilingual industrial systems,
highlighting their practicality and impact.
