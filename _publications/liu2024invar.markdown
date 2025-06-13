---
layout: publication
title: 'Invar-rag: Invariant Llm-aligned Retrieval For Better Generation'
authors: Ziwei Liu, Liang Zhang, Qian Li, Jianghua Wu, Guangxu Zhu
conference: "Arxiv"
year: 2024
bibkey: liu2024invar
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.07021"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Retrieval-augmented generation (RAG) has shown impressive capability in
providing reliable answer predictions and addressing hallucination problems. A
typical RAG implementation uses powerful retrieval models to extract external
information and large language models (LLMs) to generate answers. In contrast,
recent LLM-based retrieval has gained attention for its substantial
improvements in information retrieval (IR) due to the LLMs' semantic
understanding capability. However, directly applying LLM to RAG systems
presents challenges. This may cause feature locality problems as massive
parametric knowledge can hinder effective usage of global information across
the corpus; for example, an LLM-based retriever often inputs document summaries
instead of full documents. Moreover, various pre-trained tasks in LLMs
introduce variance, further weakening performance as a retriever.
  To address these issues, we propose a novel two-stage fine-tuning
architecture called Invar-RAG. In the retrieval stage, an LLM-based retriever
is constructed by integrating LoRA-based representation learning to tackle
feature locality issues. To enhance retrieval performance, we develop two
patterns (invariant and variant patterns) and an invariance loss to reduce LLM
variance. In the generation stage, a refined fine-tuning method is employed to
improve LLM accuracy in generating answers based on retrieved information.
Experimental results show that Invar-RAG significantly outperforms existing
baselines across three open-domain question answering (ODQA) datasets. Code is
available in the Supplementary Material for reproducibility.
