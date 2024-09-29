---
layout: publication
title: Recursive Decoding: A Situated Cognition Approach To Compositional Generation In Grounded Language Understanding
authors: Setzler Matthew, Howland Scott, Phillips Lauren
conference: "Arxiv"
year: 2022
bibkey: setzler2022recursive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.11766"}
tags: ['Applications', 'Training Techniques']
---
Compositional generalization is a troubling blind spot for neural language models. Recent efforts have presented techniques for improving a models ability to encode novel combinations of known inputs but less work has focused on generating novel combinations of known outputs. Here we focus on this latter decode-side form of generalization in the context of gSCAN a synthetic benchmark for compositional generalization in grounded language understanding. We present Recursive Decoding (RD) a novel procedure for training and using seq2seq models targeted towards decode-side generalization. Rather than generating an entire output sequence in one pass models are trained to predict one token at a time. Inputs (i.e. the external gSCAN environment) are then incrementally updated based on predicted tokens and re-encoded for the next decoder time step. RD thus decomposes a complex out-of-distribution sequence generation task into a series of incremental predictions that each resemble what the model has already seen during training. RD yields dramatic improvement on two previously neglected generalization tasks in gSCAN. We provide analyses to elucidate these gains over failure of a baseline and then discuss implications for generalization in naturalistic grounded language understanding and seq2seq more generally.
