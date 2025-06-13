---
layout: publication
title: 'Fidelis: Faithful Reasoning In Large Language Model For Knowledge Graph Question Answering'
authors: Yuan Sui, Yufei He, Nian Liu, Xiaoxin He, Kun Wang, Bryan Hooi
conference: "Arxiv"
year: 2024
bibkey: sui2024faithful
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13873"}
  - {name: "Code", url: "https://github.com/Y-Sui/FiDeLiS"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'RAG', 'Has Code', 'Interpretability and Explainability', 'Applications']
---
Large Language Models (LLMs) are often challenged by generating erroneous or hallucinated responses, especially in complex reasoning tasks. Leveraging Knowledge Graphs (KGs) as external knowledge sources has emerged as a viable solution. However, existing KG-enhanced methods, either retrieval-based or agent-based, encounter difficulties in accurately retrieving knowledge and efficiently traversing KGs at scale. In this paper, we propose a unified framework, FiDeLiS, designed to improve the factuality of LLM responses by anchoring answers to verifiable reasoning steps retrieved from KGs. To achieve this, we leverage step-wise beam search with a deductive scoring function, allowing the LLM to validate reasoning process step by step, and halt the search once the question is deducible. In addition, we propose a Path-RAG module to pre-select a smaller candidate set for each beam search step, reducing computational costs by narrowing the search space. Extensive experiments show that our method, as a training-free framework, not only improve the performance but also enhance the factuality and interpretability across different benchmarks. Code is released at https://github.com/Y-Sui/FiDeLiS.
