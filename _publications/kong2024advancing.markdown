---
layout: publication
title: 'Opentab: Advancing Large Language Models As Open-domain Table Reasoners'
authors: Kezhi Kong, Jiani Zhang, Zhengyuan Shen, Balasubramaniam Srinivasan, Chuan Lei, Christos Faloutsos, Huzefa Rangwala, George Karypis
conference: "Arxiv"
year: 2024
bibkey: kong2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14361"}
tags: ['RAG', 'Tools']
---
Large Language Models (LLMs) trained on large volumes of data excel at
various natural language tasks, but they cannot handle tasks requiring
knowledge that has not been trained on previously. One solution is to use a
retriever that fetches relevant information to expand LLM's knowledge scope.
However, existing textual-oriented retrieval-based LLMs are not ideal on
structured table data due to diversified data modalities and large table sizes.
In this work, we propose OpenTab, an open-domain table reasoning framework
powered by LLMs. Overall, OpenTab leverages table retriever to fetch relevant
tables and then generates SQL programs to parse the retrieved tables
efficiently. Utilizing the intermediate data derived from the SQL executions,
it conducts grounded inference to produce accurate response. Extensive
experimental evaluation shows that OpenTab significantly outperforms baselines
in both open- and closed-domain settings, achieving up to 21.5% higher
accuracy. We further run ablation studies to validate the efficacy of our
proposed designs of the system.
