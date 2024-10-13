---
layout: publication
title: 'Building A Question And Answer System For News Domain'
authors: Basu Sandipan, Gaddala Aravind, Chetan Pooja, Tiwari Garima, Darapaneni Narayana, Parvathaneni Sadwik, Paduri Anwesh Reddy
conference: "Arxiv"
year: 2021
bibkey: basu2021building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.05744"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
This project attempts to build a Question- Answering system in the News
Domain, where Passages will be News articles, and anyone can ask a Question
against it. We have built a span-based model using an Attention mechanism,
where the model predicts the answer to a question as to the position of the
start and end tokens in a paragraph. For training our model, we have used the
Stanford Question and Answer (SQuAD 2.0) dataset[1]. To do well on SQuAD 2.0,
systems must not only answer questions when possible but also determine when no
answer is supported by the paragraph and abstain from answering. Our model
architecture comprises three layers- Embedding Layer, RNN Layer, and the
Attention Layer. For the Embedding layer, we used GloVe and the Universal
Sentence Encoder. For the RNN Layer, we built variations of the RNN Layer
including bi-LSTM and Stacked LSTM and we built an Attention Layer using a
Context to Question Attention and also improvised on the innovative
Bidirectional Attention Layer. Our best performing model which uses GloVe
Embedding combined with Bi-LSTM and Context to Question Attention achieved an
F1 Score and EM of 33.095 and 33.094 respectively. We also leveraged transfer
learning and built a Transformer based model using BERT. The BERT-based model
achieved an F1 Score and EM of 57.513 and 49.769 respectively. We concluded
that the BERT model is superior in all aspects of answering various types of
questions.
