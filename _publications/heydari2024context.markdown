---
layout: publication
title: 'Context Awareness Gate For Retrieval Augmented Generation'
authors: Mohammad Hassan Heydari, Arshia Hemmat, Erfan Naman, Afsaneh Fatemi
conference: "Arxiv"
year: 2024
bibkey: heydari2024context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.16133'}
tags: ['Attention Mechanism', 'RAG', 'Applications', 'Model Architecture', 'Prompting']
---
Retrieval Augmented Generation (RAG) has emerged as a widely adopted approach
to mitigate the limitations of large language models (LLMs) in answering
domain-specific questions. Previous research has predominantly focused on
improving the accuracy and quality of retrieved data chunks to enhance the
overall performance of the generation pipeline. However, despite ongoing
advancements, the critical issue of retrieving irrelevant information -- which
can impair the ability of the model to utilize its internal knowledge
effectively -- has received minimal attention. In this work, we investigate the
impact of retrieving irrelevant information in open-domain question answering,
highlighting its significant detrimental effect on the quality of LLM outputs.
To address this challenge, we propose the Context Awareness Gate (CAG)
architecture, a novel mechanism that dynamically adjusts the LLMs' input prompt
based on whether the user query necessitates external context retrieval.
Additionally, we introduce the Vector Candidates method, a core mathematical
component of CAG that is statistical, LLM-independent, and highly scalable. We
further examine the distributions of relationships between contexts and
questions, presenting a statistical analysis of these distributions. This
analysis can be leveraged to enhance the context retrieval process in Retrieval
Augmented Generation (RAG) systems.
