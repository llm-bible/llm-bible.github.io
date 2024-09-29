---
layout: publication
title: L2MAC Large Language Model Automatic Computer For Extensive Code Generation
authors: Holt Samuel, Luyten Max Ruiz, Van Der Schaar Mihaela
conference: "Arxiv"
year: 2023
bibkey: holt2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02003"}
tags: ['Agentic', 'Applications', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Transformer45;based large language models (LLMs) are constrained by the fixed context window of the underlying transformer architecture hindering their ability to produce long and coherent outputs. Memory45;augmented LLMs are a promising solution but current approaches cannot handle long output generation tasks since they (1) only focus on reading memory and reduce its evolution to the concatenation of new memories or (2) use very specialized memories that cannot adapt to other domains. This paper presents L2MAC the first practical LLM45;based general45;purpose stored45;program automatic computer (von Neumann architecture) framework an LLM45;based multi45;agent system for long and consistent output generation. Its memory has two components the instruction registry which is populated with a prompt program to solve the user45;given task and a file store which will contain the final and intermediate outputs. Each instruction in turn is executed by a separate LLM agent whose context is managed by a control unit capable of precise memory reading and writing to ensure effective interaction with the file store. These components enable L2MAC to generate extensive outputs bypassing the constraints of the finite context window while producing outputs that fulfill a complex user45;specified task. We empirically demonstrate that L2MAC achieves state45;of45;the45;art performance in generating large codebases for system design tasks significantly outperforming other coding methods in implementing the detailed user45;specified task; we show that L2MAC works for general45;purpose extensive text45;based tasks such as writing an entire book; and we provide valuable insights into L2MACs performance improvement over existing methods.
