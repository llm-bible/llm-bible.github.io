---
layout: publication
title: 'Information Anxiety In Large Language Models'
authors: Prasoon Bajpai, Sarah Masud, Tanmoy Chakraborty
conference: "Arxiv"
year: 2024
bibkey: bajpai2024information
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.10813"}
tags: ['Security', 'Training Techniques', 'Pretraining Methods', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated strong performance as
knowledge repositories, enabling models to understand user queries and generate
accurate and context-aware responses. Extensive evaluation setups have
corroborated the positive correlation between the retrieval capability of LLMs
and the frequency of entities in their pretraining corpus. We take the
investigation further by conducting a comprehensive analysis of the internal
reasoning and retrieval mechanisms of LLMs. Our work focuses on three critical
dimensions - the impact of entity popularity, the models' sensitivity to
lexical variations in query formulation, and the progression of hidden state
representations across LLM layers. Our preliminary findings reveal that popular
questions facilitate early convergence of internal states toward the correct
answer. However, as the popularity of a query increases, retrieved attributes
across lexical variations become increasingly dissimilar and less accurate.
Interestingly, we find that LLMs struggle to disentangle facts, grounded in
distinct relations, from their parametric memory when dealing with highly
popular subjects. Through a case study, we explore these latent strains within
LLMs when processing highly popular queries, a phenomenon we term information
anxiety. The emergence of information anxiety in LLMs underscores the
adversarial injection in the form of linguistic variations and calls for a more
holistic evaluation of frequently occurring entities.
