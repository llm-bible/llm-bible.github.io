---
layout: publication
title: 'Retrieval-augmented Process Reward Model For Generalizable Mathematical Reasoning'
authors: Jiachen Zhu, Congmin Zheng, Jianghao Lin, Kounianhua Du, Ying Wen, Yong Yu, Jun Wang, Weinan Zhang
conference: "Arxiv"
year: 2025
bibkey: zhu2025retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14361'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques', 'Tools']
---
While large language models (LLMs) have significantly advanced mathematical
reasoning, Process Reward Models (PRMs) have been developed to evaluate the
logical validity of reasoning steps. However, PRMs still struggle with
out-of-distribution (OOD) challenges. This paper identifies key OOD issues,
including step OOD, caused by differences in reasoning patterns across model
types and sizes, and question OOD, which arises from dataset shifts between
training data and real-world problems. To address these issues, we introduce
Retrieval-Augmented Process Reward Model (RetrievalPRM), a novel framework
designed to tackle these OOD issues. By utilizing a two-stage
retrieval-enhanced mechanism, RetrievalPRM retrieves semantically similar
questions and steps as a warmup, enhancing PRM's ability to evaluate target
steps and improving generalization and reasoning consistency across different
models and problem types. Our extensive experiments demonstrate that
RetrievalPRM outperforms existing baselines across multiple real-world
datasets. Our open-source contributions include a retrieval-enhanced dataset, a
tuning framework for PRM training, and the RetrievalPRM model, establishing a
new standard for PRM performance.
