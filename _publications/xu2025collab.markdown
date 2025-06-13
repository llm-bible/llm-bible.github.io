---
layout: publication
title: 'Collab-rag: Boosting Retrieval-augmented Generation For Complex Question Answering Via White-box And Black-box LLM Collaboration'
authors: Ran Xu, Wenqi Shi, Yuchen Zhuang, Yue Yu, Joyce C. Ho, Haoyu Wang, Carl Yang
conference: "Arxiv"
year: 2025
bibkey: xu2025collab
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.04915'}
  - {name: "Code", url: 'https://github.com/ritaranx/Collab-RAG/'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools', 'Applications', 'Fine-Tuning', 'Pretraining Methods']
---
Retrieval-Augmented Generation (RAG) systems often struggle to handle
multi-hop question-answering tasks accurately due to irrelevant context
retrieval and limited complex reasoning capabilities. We introduce Collab-RAG,
a collaborative training framework that leverages mutual enhancement between a
white-box small language model (SLM) and a blackbox large language model (LLM)
for RAG. Specifically, the SLM decomposes complex queries into simpler
sub-questions, thus enhancing the accuracy of the retrieval and facilitating
more effective reasoning by the black-box LLM. Concurrently, the black-box LLM
provides feedback signals to improve the SLM's decomposition capability. We
observe that Collab-RAG relies solely on supervision from an affordable
black-box LLM without additional distillation from frontier LLMs, yet
demonstrates strong generalization across multiple black-box LLMs. Experimental
evaluations across five multi-hop QA datasets demonstrate that Collab-RAG
substantially outperforms existing black-box-only and SLM fine-tuning baselines
by 1.8%-14.2% on average. In particular, our fine-tuned 3B SLM surpasses a
frozen 32B LLM in question decomposition, highlighting the efficiency of
Collab-RAG in improving reasoning and retrieval for complex questions. The code
of Collab-RAG is available on https://github.com/ritaranx/Collab-RAG/.
