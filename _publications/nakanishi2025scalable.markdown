---
layout: publication
title: 'Scalable-softmax Is Superior For Attention'
authors: Ken M. Nakanishi
conference: "Arxiv"
year: 2025
bibkey: nakanishi2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.19399"}
tags: ['Training Techniques', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
The maximum element of the vector output by the Softmax function approaches
zero as the input vector size increases. Transformer-based language models rely
on Softmax to compute attention scores, causing the attention distribution to
flatten as the context size grows. This reduces the model's ability to
prioritize key information effectively and potentially limits its length
generalization. To address this problem, we propose Scalable-Softmax (SSMax),
which replaces Softmax in scenarios where the input vector size varies. SSMax
can be seamlessly integrated into existing Transformer-based architectures.
Experimental results in language modeling show that models using SSMax not only
achieve faster loss reduction during pretraining but also significantly improve
performance in long contexts and key information retrieval. Furthermore, an
analysis of attention scores reveals that SSMax enables the model to focus
attention on key information even in long contexts. Additionally, although
models that use SSMax from the beginning of pretraining achieve better length
generalization, those that have already started pretraining can still gain some
of this ability by replacing Softmax in the attention layers with SSMax, either
during or after pretraining.
