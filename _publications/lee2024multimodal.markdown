---
layout: publication
title: 'Multimodal Reasoning With Multimodal Knowledge Graph'
authors: Junlin Lee, Yequan Wang, Jing Li, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: lee2024multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.02030'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Applications', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods']
---
Multimodal reasoning with large language models (LLMs) often suffers from
hallucinations and the presence of deficient or outdated knowledge within LLMs.
Some approaches have sought to mitigate these issues by employing textual
knowledge graphs, but their singular modality of knowledge limits comprehensive
cross-modal understanding. In this paper, we propose the Multimodal Reasoning
with Multimodal Knowledge Graph (MR-MKG) method, which leverages multimodal
knowledge graphs (MMKGs) to learn rich and semantic knowledge across
modalities, significantly enhancing the multimodal reasoning capabilities of
LLMs. In particular, a relation graph attention network is utilized for
encoding MMKGs and a cross-modal alignment module is designed for optimizing
image-text alignment. A MMKG-grounded dataset is constructed to equip LLMs with
initial expertise in multimodal reasoning through pretraining. Remarkably,
MR-MKG achieves superior performance while training on only a small fraction of
parameters, approximately 2.25% of the LLM's parameter size. Experimental
results on multimodal question answering and multimodal analogy reasoning tasks
demonstrate that our MR-MKG method outperforms previous state-of-the-art
models.
