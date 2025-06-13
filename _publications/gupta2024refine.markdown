---
layout: publication
title: 'REFINE On Scarce Data: Retrieval Enhancement Through Fine-tuning Via Model Fusion Of Embedding Models'
authors: Ambuje Gupta, Mrinal Rawat, Andreas Stolcke, Roberto Pieraccini
conference: "Arxiv"
year: 2024
bibkey: gupta2024refine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12890"}
tags: ['Fine-Tuning', 'RAG', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
Retrieval augmented generation (RAG) pipelines are commonly used in tasks
such as question-answering (QA), relying on retrieving relevant documents from
a vector store computed using a pretrained embedding model. However, if the
retrieved context is inaccurate, the answers generated using the large language
model (LLM) may contain errors or hallucinations. Although pretrained embedding
models have advanced, adapting them to new domains remains challenging.
Fine-tuning is a potential solution, but industry settings often lack the
necessary fine-tuning data. To address these challenges, we propose REFINE, a
novel technique that generates synthetic data from available documents and then
uses a model fusion approach to fine-tune embeddings for improved retrieval
performance in new domains, while preserving out-of-domain capability. We
conducted experiments on the two public datasets: SQUAD and RAG-12000 and a
proprietary TOURISM dataset. Results demonstrate that even the standard
fine-tuning with the proposed data augmentation technique outperforms the
vanilla pretrained model. Furthermore, when combined with model fusion, the
proposed approach achieves superior performance, with a 5.76% improvement in
recall on the TOURISM dataset, and 6.58 % and 0.32% enhancement on SQUAD and
RAG-12000 respectively.
