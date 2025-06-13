---
layout: publication
title: 'Gabert -- An Irish Language Model'
authors: James Barry, Joachim Wagner, Lauren Cassidy, Alan Cowap, Teresa Lynn, Abigail Walsh, Mícheál J. Ó Meachair, Jennifer Foster
conference: "Arxiv"
year: 2021
bibkey: barry2021gabert
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2107.12930'}
tags: ['Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
The BERT family of neural language models have become highly popular due to
their ability to provide sequences of text with rich context-sensitive token
encodings which are able to generalise well to many NLP tasks. We introduce
gaBERT, a monolingual BERT model for the Irish language. We compare our gaBERT
model to multilingual BERT and the monolingual Irish WikiBERT, and we show that
gaBERT provides better representations for a downstream parsing task. We also
show how different filtering criteria, vocabulary size and the choice of
subword tokenisation model affect downstream performance. We compare the
results of fine-tuning a gaBERT model with an mBERT model for the task of
identifying verbal multiword expressions, and show that the fine-tuned gaBERT
model also performs better at this task. We release gaBERT and related code to
the community.
