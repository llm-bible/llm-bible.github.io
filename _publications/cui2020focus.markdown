---
layout: publication
title: 'Focus-constrained Attention Mechanism For Cvae-based Response Generation'
authors: Zhi Cui, Yanran Li, Jiayi Zhang, Jianwei Cui, Chen Wei, Bin Wang
conference: "Arxiv"
year: 2020
bibkey: cui2020focus
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2009.12102'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Reinforcement Learning']
---
To model diverse responses for a given post, one promising way is to
introduce a latent variable into Seq2Seq models. The latent variable is
supposed to capture the discourse-level information and encourage the
informativeness of target responses. However, such discourse-level information
is often too coarse for the decoder to be utilized. To tackle it, our idea is
to transform the coarse-grained discourse-level information into fine-grained
word-level information. Specifically, we firstly measure the semantic
concentration of corresponding target response on the post words by introducing
a fine-grained focus signal. Then, we propose a focus-constrained attention
mechanism to take full advantage of focus in well aligning the input to the
target response. The experimental results demonstrate that by exploiting the
fine-grained signal, our model can generate more diverse and informative
responses compared with several state-of-the-art models.
