---
layout: publication
title: 'Quantifying Reliance On External Information Over Parametric Knowledge During Retrieval Augmented Generation (RAG) Using Mechanistic Analysis'
authors: Reshmi Ghosh, Rahul Seetharaman, Hitesh Wadhwa, Somyaa Aggarwal, Samyadeep Basu, Soundararajan Srinivasan, Wenlong Zhao, Shreyas Chaudhari, Ehsan Aghazadeh
conference: "Arxiv"
year: 2024
bibkey: ghosh2024quantifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.00857'}
tags: ['Attention Mechanism', 'RAG', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias']
---
Retrieval Augmented Generation (RAG) is a widely used approach for leveraging
external context in several natural language applications such as question
answering and information retrieval. Yet, the exact nature in which a Language
Model (LM) leverages this non-parametric memory or retrieved context isn't
clearly understood. This paper mechanistically examines the RAG pipeline to
highlight that LMs demonstrate a "shortcut'' effect and have a strong bias
towards utilizing the retrieved context to answer questions, while relying
minimally on model priors. We propose (a) Causal Mediation Analysis; for
proving that parametric memory is minimally utilized when answering a question
and (b) Attention Contributions and Knockouts for showing the last token
residual stream do not get enriched from the subject token in the question, but
gets enriched from tokens of RAG-context. We find this pronounced "shortcut''
behaviour to be true across both LLMs (e.g.,LlaMa) and SLMs (e.g., Phi)
