---
layout: publication
title: Exploring Neural Net Augmentation to BERT for Question Answering on SQUAD 2.0
authors: Gupta Suhas
conference: "Arxiv"
year: 2019
bibkey: gupta2019exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.01767"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Enhancing machine capabilities to answer questions has been a topic of considerable focus in recent years of NLP research. Language models like Embeddings from Language Models (ELMo)1 and Bidirectional Encoder Representations from Transformers (BERT) 2 have been very successful in developing general purpose language models that can be optimized for a large number of downstream language tasks. In this work we focused on augmenting the pre-trained BERT language model with different output neural net architectures and compared their performance on question answering task posed by the Stanford Question Answering Dataset 2.0 (SQUAD 2.0) 3. Additionally we also fine-tuned the pre-trained BERT model parameters to demonstrate its effectiveness in adapting to specialized language tasks. Our best output network is the contextualized CNN that performs on both the unanswerable and answerable question answering tasks with F1 scores of 75.32 and 64.85 respectively.
