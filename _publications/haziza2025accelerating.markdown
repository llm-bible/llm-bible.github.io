---
layout: publication
title: 'Accelerating Transformer Inference And Training With 2:4 Activation Sparsity'
authors: Daniel Haziza, Timothy Chou, Dhruv Choudhary, Luca Wehrstedt, Francisco Massa, Jiecao Yu, Geonhwa Jeong, Supriya Rao, Patrick Labatut, Jesse Cai
conference: "Arxiv"
year: 2025
bibkey: haziza2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16672"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer']
---
In this paper, we demonstrate how to leverage 2:4 sparsity, a popular
hardware-accelerated GPU sparsity pattern, to activations to accelerate large
language model training and inference. Crucially we exploit the intrinsic
sparsity found in Squared-ReLU activations to provide this acceleration with no
accuracy loss. Our approach achieves up to 1.3x faster Feed Forward Network
(FFNs) in both the forwards and backwards pass. This work highlights the
potential for sparsity to play a key role in accelerating large language model
training and inference.
