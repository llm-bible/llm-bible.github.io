---
layout: publication
title: 'RAG Llms Are Not Safer: A Safety Analysis Of Retrieval-augmented Generation For Large Language Models'
authors: Bang An, Shiyue Zhang, Mark Dredze
conference: "Arxiv"
year: 2025
bibkey: an2025rag
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18041"}
tags: ['Responsible AI', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Efforts to ensure the safety of large language models (LLMs) include safety
fine-tuning, evaluation, and red teaming. However, despite the widespread use
of the Retrieval-Augmented Generation (RAG) framework, AI safety work focuses
on standard LLMs, which means we know little about how RAG use cases change a
model's safety profile. We conduct a detailed comparative analysis of RAG and
non-RAG frameworks with eleven LLMs. We find that RAG can make models less safe
and change their safety profile. We explore the causes of this change and find
that even combinations of safe models with safe documents can cause unsafe
generations. In addition, we evaluate some existing red teaming methods for RAG
settings and show that they are less effective than when used for non-RAG
settings. Our work highlights the need for safety research and red-teaming
methods specifically tailored for RAG LLMs.
