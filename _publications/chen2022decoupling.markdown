---
layout: publication
title: 'Decoupling Knowledge From Memorization: Retrieval-augmented Prompt Learning'
authors: Xiang Chen et al.
conference: Arxiv
year: 2022
citations: 23
bibkey: chen2022decoupling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.14704'}, {name: Code,
    url: 'https://github.com/zjunlp/PromptKG/tree/main/research/RetroPrompt'}]
tags: [RAG, Few-Shot, Prompting]
---
Prompt learning approaches have made waves in natural language processing by
inducing better few-shot performance while they still follow a parametric-based
learning paradigm; the oblivion and rote memorization problems in learning may
encounter unstable generalization issues. Specifically, vanilla prompt learning
may struggle to utilize atypical instances by rote during fully-supervised
training or overfit shallow patterns with low-shot data. To alleviate such
limitations, we develop RetroPrompt with the motivation of decoupling knowledge
from memorization to help the model strike a balance between generalization and
memorization. In contrast with vanilla prompt learning, RetroPrompt constructs
an open-book knowledge-store from training instances and implements a retrieval
mechanism during the process of input, training and inference, thus equipping
the model with the ability to retrieve related contexts from the training
corpus as cues for enhancement. Extensive experiments demonstrate that
RetroPrompt can obtain better performance in both few-shot and zero-shot
settings. Besides, we further illustrate that our proposed RetroPrompt can
yield better generalization abilities with new datasets. Detailed analysis of
memorization indeed reveals RetroPrompt can reduce the reliance of language
models on memorization; thus, improving generalization for downstream tasks.
Code is available in
https://github.com/zjunlp/PromptKG/tree/main/research/RetroPrompt.