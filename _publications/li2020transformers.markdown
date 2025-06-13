---
layout: publication
title: 'Transformers To Learn Hierarchical Contexts In Multiparty Dialogue For Span-based Question Answering'
authors: Changmao Li, Jinho D. Choi
conference: "Arxiv"
year: 2020
bibkey: li2020transformers
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2004.03561'}
tags: ['Language Modeling', 'Transformer', 'BERT', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
We introduce a novel approach to transformers that learns hierarchical
representations in multiparty dialogue. First, three language modeling tasks
are used to pre-train the transformers, token- and utterance-level language
modeling and utterance order prediction, that learn both token and utterance
embeddings for better understanding in dialogue contexts. Then, multi-task
learning between the utterance prediction and the token span prediction is
applied to fine-tune for span-based question answering (QA). Our approach is
evaluated on the FriendsQA dataset and shows improvements of 3.8% and 1.4% over
the two state-of-the-art transformer models, BERT and RoBERTa, respectively.
