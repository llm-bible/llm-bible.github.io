---
layout: publication
title: 'Dewey Long Context Embedding Model: A Technical Report'
authors: Dun Zhang, Panxiang Zou, Yudong Zhou
conference: "Arxiv"
year: 2025
bibkey: zhang2025dewey
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20376"}
  - {name: "Code", url: "https://huggingface.co/infgrad/dewey_en_beta"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Distillation']
---
This technical report presents the training methodology and evaluation
results of the open-source dewey_en_beta embedding model. The increasing demand
for retrieval-augmented generation (RAG) systems and the expanding context
window capabilities of large language models (LLMs) have created critical
challenges for conventional embedding models. Current approaches often struggle
to maintain semantic coherence when processing documents exceeding typical
sequence length limitations, significantly impacting retrieval performance in
knowledge-intensive applications. This paper presents dewey_en_beta, a novel
text embedding model that achieves excellent performance on MTEB (Eng, v2) and
LongEmbed benchmark while supporting 128K token sequences. Our technical
contribution centers on chunk alignment training, an innovative methodology
that enables the simultaneous generation of localized chunk embeddings and
global document-level representations through distillation. Information
regarding the model release can be found at
https://huggingface.co/infgrad/dewey_en_beta.
