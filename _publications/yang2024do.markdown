---
layout: publication
title: 'Do Large Language Models Perform Latent Multi-hop Reasoning Without Exploiting Shortcuts?'
authors: Sohee Yang, Nora Kassner, Elena Gribovskaya, Sebastian Riedel, Mor Geva
conference: "Arxiv"
year: 2024
bibkey: yang2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16679"}
tags: ['Pretraining Methods', 'Training Techniques', 'Reinforcement Learning']
---
We evaluate how well Large Language Models (LLMs) latently recall and compose facts to answer multi-hop queries like "In the year Scarlett Johansson was born, the Summer Olympics were hosted in the country of". One major challenge in such evaluation is that LLMs may have developed shortcuts by encountering the head entity "Scarlett Johansson" and the answer entity "United States" in the same training sequences or merely guess the answer based on frequency-based priors. To prevent shortcuts, we exclude test queries where the head and answer entities might have co-appeared during training. Through careful selection of relations and facts and systematic removal of cases where models might guess answers or exploit partial matches, we construct an evaluation dataset SOCRATES (ShOrtCut-fRee lATent rEaSoning). We observe that LLMs demonstrate promising latent multi-hop reasoning abilities without exploiting shortcuts, but only for certain types of queries. For queries requiring latent recall of countries as the intermediate answer, the best models achieve 80% latent composability, but this drops to just 5% for the recall of years. Comparisons with Chain-of-Thought highlight a significant gap between the ability of models to reason latently versus explicitly. Analysis reveals that latent representations of the intermediate answer are constructed more often in queries with higher latent composability, and shows the emergence of latent multi-hop reasoning during pretraining.
