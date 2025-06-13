---
layout: publication
title: 'KG-RAG: Bridging The Gap Between Knowledge And Creativity'
authors: Diego Sanmartin
conference: "Arxiv"
year: 2024
bibkey: sanmartin2024kg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12035"}
tags: ['Agentic', 'Tools', 'RAG', 'Fine-Tuning', 'Applications']
---
Ensuring factual accuracy while maintaining the creative capabilities of
Large Language Model Agents (LMAs) poses significant challenges in the
development of intelligent agent systems. LMAs face prevalent issues such as
information hallucinations, catastrophic forgetting, and limitations in
processing long contexts when dealing with knowledge-intensive tasks. This
paper introduces a KG-RAG (Knowledge Graph-Retrieval Augmented Generation)
pipeline, a novel framework designed to enhance the knowledge capabilities of
LMAs by integrating structured Knowledge Graphs (KGs) with the functionalities
of LLMs, thereby significantly reducing the reliance on the latent knowledge of
LLMs. The KG-RAG pipeline constructs a KG from unstructured text and then
performs information retrieval over the newly created graph to perform KGQA
(Knowledge Graph Question Answering). The retrieval methodology leverages a
novel algorithm called Chain of Explorations (CoE) which benefits from LLMs
reasoning to explore nodes and relationships within the KG sequentially.
Preliminary experiments on the ComplexWebQuestions dataset demonstrate notable
improvements in the reduction of hallucinated content and suggest a promising
path toward developing intelligent systems adept at handling
knowledge-intensive tasks.
