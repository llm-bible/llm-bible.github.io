---
layout: publication
title: Large Language Models Can Better Understand Knowledge Graphs Than We Thought
authors: Dai Xinbang, Hua Yuncheng, Wu Tongtong, Sheng Yang, Ji Qiu, Qi Guilin
conference: "Arxiv"
year: 2024
bibkey: dai2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11541"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Training Techniques']
---
As the parameter scale of large language models (LLMs) grows jointly training knowledge graph (KG) embeddings with model parameters to enhance LLM capabilities becomes increasingly costly. Consequently the community has shown interest in developing prompt strategies that effectively integrate KG information into LLMs. However the format for incorporating KGs into LLMs lacks standardization; for instance KGs can be transformed into linearized triples or natural language (NL) text. Current prompting methods often rely on a trial-and-error approach leaving researchers with an incomplete understanding of which KG input format best facilitates LLM comprehension of KG content. To elucidate this we design a series of experiments to explore LLMs understanding of different KG input formats within the context of prompt engineering. Our analysis examines both literal and attention distribution levels. Through extensive experiments we indicate a counter-intuitive phenomenon when addressing fact-related questions unordered linearized triples are more effective for LLMs understanding of KGs compared to fluent NL text. Furthermore noisy incomplete or marginally relevant subgraphs can still enhance LLM performance. Finally different LLMs have distinct preferences for different formats of organizing unordered triples.
