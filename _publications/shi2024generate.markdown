---
layout: publication
title: Generate45;then45;ground In Retrieval45;augmented Generation For Multi45;hop Question Answering
authors: Shi Zhengliang, Zhang Shuo, Sun Weiwei, Gao Shen, Ren Pengjie, Chen Zhumin, Ren Zhaochun
conference: "Arxiv"
year: 2024
bibkey: shi2024generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14891"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Tools']
---
Multi45;Hop Question Answering (MHQA) tasks present a significant challenge for large language models (LLMs) due to the intensive knowledge required. Current solutions like Retrieval45;Augmented Generation typically retrieve potential documents from an external corpus to read an answer. However the performance of this retrieve45;then45;read paradigm is constrained by the retriever and the inevitable noise in the retrieved documents. To mitigate these challenges we introduce a novel generate45;then45;ground (GenGround) framework synergizing the parametric knowledge of LLMs and external documents to solve a multi45;hop question. GenGround empowers LLMs to alternate two phases until the final answer is derived (1) formulate a simpler single45;hop question and directly generate the answer; (2) ground the question45;answer pair in retrieved documents amending any wrong predictions in the answer. We also propose an instructional grounding distillation method to generalize our method into smaller models. Extensive experiments conducted on four datasets illustrate the superiority of our method.
