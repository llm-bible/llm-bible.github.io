---
layout: publication
title: 'Simulating Task-oriented Dialogues With State Transition Graphs And Large Language Models'
authors: Samarinas Chris, Promthaw Pracha, Nijasure Atharva, Zeng Hansi, Killingback Julian, Zamani Hamed
conference: "Arxiv"
year: 2024
bibkey: samarinas2024simulating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14772"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning']
---
This paper explores SynTOD a new synthetic data generation approach for developing end-to-end Task-Oriented Dialogue (TOD) Systems capable of handling complex tasks such as intent classification slot filling conversational question-answering and retrieval-augmented response generation without relying on crowdsourcing or real-world data. SynTOD utilizes a state transition graph to define the desired behavior of a TOD system and generates diverse structured conversations through random walks and response simulation using large language models (LLMs). In our experiments using graph-guided response simulations leads to significant improvements in intent classification slot filling and response relevance compared to naive single-prompt simulated conversations. We also investigate the end-to-end TOD effectiveness of different base and instruction-tuned LLMs with and without the constructed synthetic conversations. Finally we explore how various LLMs can evaluate responses in a TOD system and how well they are correlated with human judgments. Our findings pave the path towards quick development and evaluation of domain-specific TOD systems. We release our datasets models and code for research purposes.
