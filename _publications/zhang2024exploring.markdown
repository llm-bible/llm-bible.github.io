---
layout: publication
title: 'Exploring The Best Practices Of Query Expansion With Large Language Models'
authors: Zhang Le, Wu Yihong, Yang Qian, Nie Jian-yun
conference: "Arxiv"
year: 2024
bibkey: zhang2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06311"}
  - {name: "Code", url: "https://github.com/lezhang7/Retrieval_MuGI"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) are foundational in language technologies particularly in information retrieval (IR). Previous studies have utilized LLMs for query expansion achieving notable improvements in IR. In this paper we thoroughly explore the best practice of leveraging LLMs for query expansion. To this end we introduce a training-free straightforward yet effective framework called Multi-Text Generation Integration (textscMuGI). It leverages LLMs to generate multiple pseudo-references integrating them with queries to enhance both sparse and dense retrievers. Our empirical findings reveal that (1) Increasing the number of samples from LLMs benefits IR systems; (2) A balance between the query and pseudo-documents and an effective integration strategy is critical for high performance; (3) Contextual information from LLMs is essential even boost a 23M model to outperform a 7B baseline model; (4) Pseudo relevance feedback can further calibrate queries for improved performance; and (5) Query expansion is widely applicable and versatile consistently enhancing models ranging from 23M to 7B parameters. Our code and all generated references are made available at urlhttps://github.com/lezhang7/Retrieval\_MuGI\}"
