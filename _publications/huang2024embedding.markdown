---
layout: publication
title: 'Embedding-informed Adaptive Retrieval-augmented Generation Of Large Language Models'
authors: Chengkai Huang, Yu Xia, Rui Wang, Kaige Xie, Tong Yu, Julian Mcauley, Lina Yao
conference: "Arxiv"
year: 2024
bibkey: huang2024embedding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03514"}
tags: ['Training Techniques', 'RAG', 'Pre-Training', 'Prompting']
---
Retrieval-augmented large language models (LLMs) have been remarkably
competent in various NLP tasks. However, it was observed by previous works that
retrieval is not always helpful, especially when the LLM is already
knowledgeable on the query to answer. Motivated by this, Adaptive
Retrieval-Augmented Generation (ARAG) studies retrieving only when the
knowledge asked by the query is absent in the LLM. Previous works of ARAG
either require accessing the pre-training corpus or prompting with additional
model inferences. Aiming to avoid such drawbacks, we propose to determine
whether the model is knowledgeable on a query via inspecting the
(contextualized) pre-trained token embeddings of LLMs. We hypothesize that such
embeddings capture rich information on the model's intrinsic knowledge base,
which enables an efficient way of judging the necessity to retrieve from an
external corpus. Extensive experiments demonstrate our ARAG approach's superior
performance across various benchmarks.
