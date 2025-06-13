---
layout: publication
title: 'Tanet: Thread-aware Pretraining For Abstractive Conversational Summarization'
authors: Ze Yang, Liran Wang, Zhoujin Tian, Wei Wu, Zhoujun Li
conference: "Arxiv"
year: 2022
bibkey: yang2022thread
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2204.04504'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
Although pre-trained language models (PLMs) have achieved great success and
become a milestone in NLP, abstractive conversational summarization remains a
challenging but less studied task. The difficulty lies in two aspects. One is
the lack of large-scale conversational summary data. Another is that applying
the existing pre-trained models to this task is tricky because of the
structural dependence within the conversation and its informal expression, etc.
In this work, we first build a large-scale (11M) pretraining dataset called
RCS, based on the multi-person discussions in the Reddit community. We then
present TANet, a thread-aware Transformer-based network. Unlike the existing
pre-trained models that treat a conversation as a sequence of sentences, we
argue that the inherent contextual dependency among the utterances plays an
essential role in understanding the entire conversation and thus propose two
new techniques to incorporate the structural information into our model. The
first is thread-aware attention which is computed by taking into account the
contextual dependency within utterances. Second, we apply thread prediction
loss to predict the relations between utterances. We evaluate our model on four
datasets of real conversations, covering types of meeting transcripts,
customer-service records, and forum threads. Experimental results demonstrate
that TANET achieves a new state-of-the-art in terms of both automatic
evaluation and human judgment.
