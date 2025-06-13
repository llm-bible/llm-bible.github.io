---
layout: publication
title: 'You Only Need One Model For Open-domain Question Answering'
authors: Haejun Lee, Akhil Kedia, Jongwon Lee, Ashwin Paranjape, Christopher D. Manning, Kyoung-gu Woo
conference: "Arxiv"
year: 2021
bibkey: lee2021you
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.07381"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Pre-Training', 'Applications', 'Attention Mechanism']
---
Recent approaches to Open-domain Question Answering refer to an external
knowledge base using a retriever model, optionally rerank passages with a
separate reranker model and generate an answer using another reader model.
Despite performing related tasks, the models have separate parameters and are
weakly-coupled during training. We propose casting the retriever and the
reranker as internal passage-wise attention mechanisms applied sequentially
within the transformer architecture and feeding computed representations to the
reader, with the hidden representations progressively refined at each stage.
This allows us to use a single question answering model trained end-to-end,
which is a more efficient use of model capacity and also leads to better
gradient flow. We present a pre-training method to effectively train this
architecture and evaluate our model on the Natural Questions and TriviaQA open
datasets. For a fixed parameter budget, our model outperforms the previous
state-of-the-art model by 1.0 and 0.7 exact match scores.
