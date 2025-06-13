---
layout: publication
title: 'Prompt-guided Retrieval Augmentation For Non-knowledge-intensive Tasks'
authors: Zhicheng Guo, Sijie Cheng, Yile Wang, Peng Li, Yang Liu
conference: "Arxiv"
year: 2023
bibkey: guo2023prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.17653"}
  - {name: "Code", url: "https://github.com/THUNLP-MT/PGRA"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Attention Mechanism']
---
Retrieval-augmented methods have received increasing attention to support
downstream tasks by leveraging useful information from external resources.
Recent studies mainly focus on exploring retrieval to solve knowledge-intensive
(KI) tasks. However, the potential of retrieval for most
non-knowledge-intensive (NKI) tasks remains under-explored. There are two main
challenges to leveraging retrieval-augmented methods for NKI tasks: 1) the
demand for diverse relevance score functions and 2) the dilemma between
training cost and task performance. To address these challenges, we propose a
two-stage framework for NKI tasks, named PGRA. In the first stage, we adopt a
task-agnostic retriever to build a shared static index and select candidate
evidence efficiently. In the second stage, we design a prompt-guided reranker
to rerank the nearest evidence according to task-specific relevance for the
reader. Experimental results show that PGRA outperforms other state-of-the-art
retrieval-augmented methods. Our analyses further investigate the influence
factors to model performance and demonstrate the generality of PGRA. Codes are
available at https://github.com/THUNLP-MT/PGRA.
