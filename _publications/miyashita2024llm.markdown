---
layout: publication
title: 'LLM As HPC Expert: Extending RAG Architecture For HPC Data'
authors: Yusuke Miyashita, Patrick Kin Man Tung, Johan Barthélemy
conference: "Arxiv"
year: 2024
bibkey: miyashita2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14733"}
tags: ['Security', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG']
---
High-Performance Computing (HPC) is crucial for performing advanced
computational tasks, yet their complexity often challenges users, particularly
those unfamiliar with HPC-specific commands and workflows. This paper
introduces Hypothetical Command Embeddings (HyCE), a novel method that extends
Retrieval-Augmented Generation (RAG) by integrating real-time, user-specific
HPC data, enhancing accessibility to these systems. HyCE enriches large
language models (LLM) with real-time, user-specific HPC information, addressing
the limitations of fine-tuned models on such data. We evaluate HyCE using an
automated RAG evaluation framework, where the LLM itself creates synthetic
questions from the HPC data and serves as a judge, assessing the efficacy of
the extended RAG with the evaluation metrics relevant for HPC tasks.
Additionally, we tackle essential security concerns, including data privacy and
command execution risks, associated with deploying LLMs in HPC environments.
This solution provides a scalable and adaptable approach for HPC clusters to
leverage LLMs as HPC expert, bridging the gap between users and the complex
systems of HPC.
