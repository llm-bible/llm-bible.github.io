---
layout: publication
title: CAR Conceptualization45;augmented Reasoner For Zero45;shot Commonsense Question Answering
authors: Wang Weiqi, Fang Tianqing, Ding Wenxuan, Xu Baixuan, Liu Xin, Song Yangqiu, Bosselut Antoine
conference: "Arxiv"
year: 2023
bibkey: wang2023conceptualization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14869"}
  - {name: "Code", url: "https://github.com/HKUST&#45;KnowComp/CAR"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The task of zero45;shot commonsense question answering evaluates models on their capacity to reason about general scenarios beyond those presented in specific datasets. Existing approaches for tackling this task leverage external knowledge from CommonSense Knowledge Bases (CSKBs) by pretraining the model on synthetic QA pairs constructed from CSKBs. In these approaches negative examples (distractors) are formulated by randomly sampling from CSKBs using fairly primitive keyword constraints. However two bottlenecks limit these approaches the inherent incompleteness of CSKBs limits the semantic coverage of synthetic QA pairs and the lack of human annotations makes the sampled negative examples potentially uninformative and contradictory. To tackle these limitations above we propose Conceptualization45;Augmented Reasoner (CAR) a zero45;shot commonsense question45;answering framework that fully leverages the power of conceptualization. Specifically CAR abstracts a commonsense knowledge triple to many higher45;level instances which increases the coverage of CSKB and expands the ground45;truth answer space reducing the likelihood of selecting false45;negative distractors. Extensive experiments demonstrate that CAR more robustly generalizes to answering questions about zero45;shot commonsense scenarios than existing methods including large language models such as GPT3.5 and ChatGPT. Our codes data and model checkpoints are available at https://github.com/HKUST&#45;KnowComp/CAR.
