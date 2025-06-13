---
layout: publication
title: 'TLDR: Token Loss Dynamic Reweighting For Reducing Repetitive Utterance Generation'
authors: Shaojie Jiang, Thomas Wolf, Christof Monz, Maarten De Rijke
conference: "Arxiv"
year: 2020
bibkey: jiang2020token
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2003.11963'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
Natural Language Generation (NLG) models are prone to generating repetitive
utterances. In this work, we study the repetition problem for encoder-decoder
models, using both recurrent neural network (RNN) and transformer
architectures. To this end, we consider the chit-chat task, where the problem
is more prominent than in other tasks that need encoder-decoder architectures.
We first study the influence of model architectures. By using pre-attention and
highway connections for RNNs, we manage to achieve lower repetition rates.
However, this method does not generalize to other models such as transformers.
We hypothesize that the deeper reason is that in the training corpora, there
are hard tokens that are more difficult for a generative model to learn than
others and, once learning has finished, hard tokens are still under-learned, so
that repetitive generations are more likely to happen. Based on this
hypothesis, we propose token loss dynamic reweighting (TLDR) that applies
differentiable weights to individual token losses. By using higher weights for
hard tokens and lower weights for easy tokens, NLG models are able to learn
individual tokens at different paces. Experiments on chit-chat benchmark
datasets show that TLDR is more effective in repetition reduction for both RNN
and transformer architectures than baselines using different weighting
functions.
