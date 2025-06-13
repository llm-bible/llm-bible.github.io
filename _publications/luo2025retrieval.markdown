---
layout: publication
title: 'Rallrec+: Retrieval Augmented Large Language Model Recommendation With Reasoning'
authors: Sichun Luo, Jian Xu, Xiaojie Zhang, Linrong Wang, Sicong Liu, Hanxu Hou, Linqi Song
conference: "Arxiv"
year: 2025
bibkey: luo2025retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20430"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Merging', 'RecSys', 'LREC', 'Prompting']
---
Large Language Models (LLMs) have been integrated into recommender systems to
enhance user behavior comprehension. The Retrieval Augmented Generation (RAG)
technique is further incorporated into these systems to retrieve more relevant
items and improve system performance. However, existing RAG methods have two
shortcomings. \textit\{(i)\} In the \textit\{retrieval\} stage, they rely primarily
on textual semantics and often fail to incorporate the most relevant items,
thus constraining system effectiveness. \textit\{(ii)\} In the
\textit\{generation\} stage, they lack explicit chain-of-thought reasoning,
further limiting their potential.
  In this paper, we propose Representation learning and \textbf\{R\}easoning
empowered retrieval-\textbf\{A\}ugmented \textbf\{L\}arge \textbf\{L\}anguage model
\textbf\{Rec\}ommendation (RALLRec+). Specifically, for the retrieval stage, we
prompt LLMs to generate detailed item descriptions and perform joint
representation learning, combining textual and collaborative signals extracted
from the LLM and recommendation models, respectively. To account for the
time-varying nature of user interests, we propose a simple yet effective
reranking method to capture preference dynamics. For the generation phase, we
first evaluate reasoning LLMs on recommendation tasks, uncovering valuable
insights. Then we introduce knowledge-injected prompting and consistency-based
merging approach to integrate reasoning LLMs with general-purpose LLMs,
enhancing overall performance. Extensive experiments on three real world
datasets validate our method's effectiveness.
