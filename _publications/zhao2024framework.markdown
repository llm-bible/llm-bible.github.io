---
layout: publication
title: SLIDE A Framework Integrating Small And Large Language Models For Open45;domain Dialogues Evaluation
authors: Zhao Kun, Yang Bohao, Tang Chen, Lin Chenghua, Zhan Liang
conference: "Arxiv"
year: 2024
bibkey: zhao2024framework
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15924"}
tags: ['Applications', 'Ethics And Bias', 'Pretraining Methods', 'RAG', 'Tools']
---
The long45;standing one45;to45;many problem of gold standard responses in open45;domain dialogue systems presents challenges for automatic evaluation metrics. Though prior works have demonstrated some success by applying powerful Large Language Models (LLMs) existing approaches still struggle with the one45;to45;many problem and exhibit subpar performance in domain45;specific scenarios. We assume the commonsense reasoning biases within LLMs may hinder their performance in domainspecific evaluations. To address both issues we propose a novel framework SLIDE (Small and Large Integrated for Dialogue Evaluation) that leverages both a small specialised model (SLM) and LLMs for the evaluation of open domain dialogues. Our approach introduces several techniques (1) Contrastive learning to differentiate between robust and non45;robust response embeddings; (2) A novel metric for semantic sensitivity that combines embedding cosine distances with similarity learned through neural networks and (3) a strategy for incorporating the evaluation results from both the SLM and LLMs. Our empirical results demonstrate that our approach achieves state45;of45;the45;art performance in both the classification and evaluation tasks and additionally the SLIDE evaluator exhibits better correlation with human judgements. Our code is available at https github.com/hegehongcha/SLIDE45;ACL2024.
