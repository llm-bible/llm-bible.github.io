---
layout: publication
title: 'Towards Adaptive Memory-based Optimization For Enhanced Retrieval-augmented Generation'
authors: Qitao Qin, Yucong Luo, Yihang Lu, Zhibo Chu, Xianwei Meng
conference: "Arxiv"
year: 2025
bibkey: qin2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.05312'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/Amber-B203/'}
tags: ['RAG', 'Has Code', 'Efficiency and Optimization', 'Agentic']
---
Retrieval-Augmented Generation (RAG), by integrating non-parametric knowledge
from external knowledge bases into models, has emerged as a promising approach
to enhancing response accuracy while mitigating factual errors and
hallucinations. This method has been widely applied in tasks such as Question
Answering (QA). However, existing RAG methods struggle with open-domain QA
tasks because they perform independent retrieval operations and directly
incorporate the retrieved information into generation without maintaining a
summarizing memory or using adaptive retrieval strategies, leading to noise
from redundant information and insufficient information integration. To address
these challenges, we propose Adaptive memory-based optimization for enhanced
RAG (Amber) for open-domain QA tasks, which comprises an Agent-based Memory
Updater, an Adaptive Information Collector, and a Multi-granular Content
Filter, working together within an iterative memory updating paradigm.
Specifically, Amber integrates and optimizes the language model's memory
through a multi-agent collaborative approach, ensuring comprehensive knowledge
integration from previous retrieval steps. It dynamically adjusts retrieval
queries and decides when to stop retrieval based on the accumulated knowledge,
enhancing retrieval efficiency and effectiveness. Additionally, it reduces
noise by filtering irrelevant content at multiple levels, retaining essential
information to improve overall model performance. We conduct extensive
experiments on several open-domain QA datasets, and the results demonstrate the
superiority and effectiveness of our method and its components. The source code
is available \footnote\{https://anonymous.4open.science/r/Amber-B203/\}.
