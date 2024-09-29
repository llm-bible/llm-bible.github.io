---
layout: publication
title: 'Prosg: Using Prompt Synthetic Gradients To Alleviate Prompt Forgetting Of Rnn-like Language Models'
authors: Luo Haotian, Wu Kunming, Dai Cheng, Ding Sixian, Chen Xinhao
conference: "Arxiv"
year: 2023
bibkey: luo2023using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.01981"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
RNN-like language models are getting renewed attention from NLP researchers in recent years and several models have made significant progress which demonstrates performance comparable to traditional transformers. However due to the recurrent nature of RNNs this kind of language model can only store information in a set of fixed-length state vectors. As a consequence they still suffer from forgetfulness though after a lot of improvements and optimizations when given complex instructions or prompts. As the prompted generation is the main and most concerned function of LMs solving the problem of forgetting in the process of generation is no wonder of vital importance. In this paper focusing on easing the prompt forgetting during generation we proposed an architecture to teach the model memorizing prompt during generation by synthetic gradient. To force the model to memorize the prompt we derive the states that encode the prompt then transform it into model parameter modification using low-rank gradient approximation which hard-codes the prompt into model parameters temporarily. We construct a dataset for experiments and the results have demonstrated the effectiveness of our method in solving the problem of forgetfulness in the process of prompted generation. We will release all the code upon acceptance.
