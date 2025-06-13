---
layout: publication
title: 'Lore: Logit-ranked Retriever Ensemble For Enhancing Open-domain Question Answering'
authors: Saikrishna Sanniboina, Shiv Trivedi, Sreenidhi Vijayaraghavan
conference: "Arxiv"
year: 2024
bibkey: sanniboina2024logit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10042"}
tags: ['Transformer', 'Ethics and Bias', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Retrieval-based question answering systems often suffer from positional bias,
leading to suboptimal answer generation. We propose LoRE (Logit-Ranked
Retriever Ensemble), a novel approach that improves answer accuracy and
relevance by mitigating positional bias. LoRE employs an ensemble of diverse
retrievers, such as BM25 and sentence transformers with FAISS indexing. A key
innovation is a logit-based answer ranking algorithm that combines the logit
scores from a large language model (LLM), with the retrieval ranks of the
passages. Experimental results on NarrativeQA, SQuAD demonstrate that LoRE
significantly outperforms existing retrieval-based methods in terms of exact
match and F1 scores. On SQuAD, LoRE achieves 14.5%, 22.83%, and 14.95%
improvements over the baselines for ROUGE-L, EM, and F1, respectively.
Qualitatively, LoRE generates more relevant and accurate answers, especially
for complex queries.
