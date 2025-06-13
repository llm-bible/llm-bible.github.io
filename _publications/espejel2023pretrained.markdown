---
layout: publication
title: 'Jacotext: A Pretrained Model For Java Code-text Generation'
authors: Jessica López Espejel, Mahaman Sanoussi Yahaya Alassan, Walid Dahhane, El Hassane Ettifouri
conference: "Espejel J. L. Alassan M. S. Y. Dahhane W. Ettifouri E. H. (2023). JaCoText A Pretrained Model for Java Code-Text Generation. International Journal of Computer and Systems Engineering 17(2) 100-105"
year: 2023
bibkey: espejel2023pretrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12869"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Transformer', 'Fine-Tuning', 'Applications']
---
Pretrained transformer-based models have shown high performance in natural
language generation task. However, a new wave of interest has surged: automatic
programming language generation. This task consists of translating natural
language instructions to a programming code. Despite the fact that well-known
pretrained models on language generation have achieved good performance in
learning programming languages, effort is still needed in automatic code
generation. In this paper, we introduce JaCoText, a model based on Transformers
neural network. It aims to generate java source code from natural language
text. JaCoText leverages advantages of both natural language and code
generation models. More specifically, we study some findings from the state of
the art and use them to (1) initialize our model from powerful pretrained
models, (2) explore additional pretraining on our java dataset, (3) carry out
experiments combining the unimodal and bimodal data in the training, and (4)
scale the input and output length during the fine-tuning of the model.
Conducted experiments on CONCODE dataset show that JaCoText achieves new
state-of-the-art results.
