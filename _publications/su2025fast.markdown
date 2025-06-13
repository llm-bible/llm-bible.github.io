---
layout: publication
title: 'Fast Or Better? Balancing Accuracy And Cost In Retrieval-augmented Generation With Flexible User Control'
authors: Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie
conference: "Arxiv"
year: 2025
bibkey: su2025fast
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12145'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Tools', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) has emerged as a powerful approach to
mitigate large language model (LLM) hallucinations by incorporating external
knowledge retrieval. However, existing RAG frameworks often apply retrieval
indiscriminately,leading to inefficiencies-over-retrieving when unnecessary or
failing to retrieve iteratively when required for complex reasoning. Recent
adaptive retrieval strategies, though adaptively navigates these retrieval
strategies, predict only based on query complexity and lacks user-driven
flexibility, making them infeasible for diverse user application needs. In this
paper, we introduce a novel user-controllable RAG framework that enables
dynamic adjustment of the accuracy-cost trade-off. Our approach leverages two
classifiers: one trained to prioritize accuracy and another to prioritize
retrieval efficiency. Via an interpretable control parameter \\(\alpha\\), users
can seamlessly navigate between minimal-cost retrieval and high-accuracy
retrieval based on their specific requirements. We empirically demonstrate that
our approach effectively balances accuracy, retrieval cost, and user
controllability, making it a practical and adaptable solution for real-world
applications.
