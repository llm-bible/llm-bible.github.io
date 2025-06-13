---
layout: publication
title: 'Ragviz: Diagnose And Visualize Retrieval-augmented Generation'
authors: Tevin Wang, Jingyuan He, Chenyan Xiong
conference: "Arxiv"
year: 2024
bibkey: wang2024diagnose
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01751"}
  - {name: "Code", url: "https://github.com/cxcscmu/RAGViz"}
  - {name: "Code", url: "https://youtu.be/cTAbuTu6ur4"}
tags: ['RAG', 'Model Architecture', 'Reinforcement Learning', 'Interpretability', 'Attention Mechanism', 'Has Code']
---
Retrieval-augmented generation (RAG) combines knowledge from domain-specific
sources into large language models to ground answer generation. Current RAG
systems lack customizable visibility on the context documents and the model's
attentiveness towards such documents. We propose RAGViz, a RAG diagnosis tool
that visualizes the attentiveness of the generated tokens in retrieved
documents. With a built-in user interface, retrieval index, and Large Language
Model (LLM) backbone, RAGViz provides two main functionalities: (1) token and
document-level attention visualization, and (2) generation comparison upon
context document addition and removal. As an open-source toolkit, RAGViz can be
easily hosted with a custom embedding model and HuggingFace-supported LLM
backbone. Using a hybrid ANN (Approximate Nearest Neighbor) index,
memory-efficient LLM inference tool, and custom context snippet method, RAGViz
operates efficiently with a median query time of about 5 seconds on a moderate
GPU node. Our code is available at https://github.com/cxcscmu/RAGViz. A demo
video of RAGViz can be found at https://youtu.be/cTAbuTu6ur4.
