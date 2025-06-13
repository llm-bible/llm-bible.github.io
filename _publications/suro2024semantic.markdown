---
layout: publication
title: 'Semantic Tokens In Retrieval Augmented Generation'
authors: Joel Suro
conference: "Arxiv"
year: 2024
bibkey: suro2024semantic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.02563"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Attention Mechanism']
---
Retrieval-Augmented Generation (RAG) architectures have recently garnered
significant attention for their ability to improve truth grounding and
coherence in natural language processing tasks. However, the reliability of RAG
systems in producing accurate answers diminishes as the volume of data they
access increases. Even with smaller datasets, these systems occasionally fail
to address simple queries. This issue arises from their dependence on
state-of-the-art large language models (LLMs), which can introduce uncertainty
into the system's outputs. In this work, I propose a novel Comparative RAG
system that introduces an evaluator module to bridge the gap between
probabilistic RAG systems and deterministically verifiable responses. The
evaluator compares external recommendations with the retrieved document chunks,
adding a decision-making layer that enhances the system's reliability. This
approach ensures that the chunks retrieved are both semantically relevant and
logically consistent with deterministic insights, thereby improving the
accuracy and overall efficiency of RAG systems. This framework paves the way
for more reliable and scalable question-answering applications in domains
requiring high precision and verifiability.
