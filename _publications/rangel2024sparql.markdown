---
layout: publication
title: SPARQL Generation\: An Analysis On Fine-tuning Openllama For Question Answering Over A Life Science Knowledge Graph
authors: Rangel Julio C., De Farias Tarcisio Mendes, Sima Ana Claudia, Kobayashi Norio
conference: "Arxiv"
year: 2024
bibkey: rangel2024sparql
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04627"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'TACL', 'Training Techniques']
---
The recent success of Large Language Models (LLM) in a wide range of Natural Language Processing applications opens the path towards novel Question Answering Systems over Knowledge Graphs leveraging LLMs. However one of the main obstacles preventing their implementation is the scarcity of training data for the task of translating questions into corresponding SPARQL queries particularly in the case of domain-specific KGs. To overcome this challenge in this study we evaluate several strategies for fine-tuning the OpenLlama LLM for question answering over life science knowledge graphs. In particular we propose an end-to-end data augmentation approach for extending a set of existing queries over a given knowledge graph towards a larger dataset of semantically enriched question-to-SPARQL query pairs enabling fine-tuning even for datasets where these pairs are scarce. In this context we also investigate the role of semantic clues in the queries such as meaningful variable names and inline comments. Finally we evaluate our approach over the real-world Bgee gene expression knowledge graph and we show that semantic clues can improve model performance by up to 3337; compared to a baseline with random variable names and no comments included.
