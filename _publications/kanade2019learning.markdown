---
layout: publication
title: Learning And Evaluating Contextual Embedding Of Source Code
authors: Kanade Aditya, Maniatis Petros, Balakrishnan Gogul, Shi Kensen
conference: "Arxiv"
year: 2019
bibkey: kanade2019learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.00059"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent research has achieved impressive results on understanding and improving source code by building up on machine45;learning techniques developed for natural languages. A significant advancement in natural45;language understanding has come with the development of pre45;trained contextual embeddings such as BERT which can be fine45;tuned for downstream tasks with less labeled data and training budget while achieving better accuracies. However there is no attempt yet to obtain a high45;quality contextual embedding of source code and to evaluate it on multiple program45;understanding tasks simultaneously; that is the gap that this paper aims to mitigate. Specifically first we curate a massive deduplicated corpus of 7.4M Python files from GitHub which we use to pre45;train CuBERT an open45;sourced code45;understanding BERT model; and second we create an open45;sourced benchmark that comprises five classification tasks and one program45;repair task akin to code45;understanding tasks proposed in the literature before. We fine45;tune CuBERT on our benchmark tasks and compare the resulting models to different variants of Word2Vec token embeddings BiLSTM and Transformer models as well as published state45;of45;the45;art models showing that CuBERT outperforms them all even with shorter training and with fewer labeled examples. Future work on source45;code embedding can benefit from reusing our benchmark and from comparing against CuBERT models as a strong baseline.
