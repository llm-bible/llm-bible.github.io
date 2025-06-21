---
layout: publication
title: Latent Attention For If-then Program Synthesis
authors: Xinyun Chen, Chang Liu, Richard Shin, Dawn Song, Mingcheng Chen
conference: Arxiv
year: 2016
citations: 37
bibkey: chen2016latent
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.01867'}]
tags: [RAG, Training Techniques, Attention Mechanism, Model Architecture]
---
Automatic translation from natural language descriptions into programs is a
longstanding challenging problem. In this work, we consider a simple yet
important sub-problem: translation from textual descriptions to If-Then
programs. We devise a novel neural network architecture for this task which we
train end-to-end. Specifically, we introduce Latent Attention, which computes
multiplicative weights for the words in the description in a two-stage process
with the goal of better leveraging the natural language structures that
indicate the relevant parts for predicting program elements. Our architecture
reduces the error rate by 28.57% compared to prior art. We also propose a
one-shot learning scenario of If-Then program synthesis and simulate it with
our existing dataset. We demonstrate a variation on the training procedure for
this scenario that outperforms the original procedure, significantly closing
the gap to the model trained with all data.