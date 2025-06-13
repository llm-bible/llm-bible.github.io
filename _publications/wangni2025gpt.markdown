---
layout: publication
title: 'GPT Carry-on: Training Foundation Model For Customization Could Be Simple, Scalable And Affordable'
authors: Jianqiao Wangni
conference: "Arxiv"
year: 2025
bibkey: wangni2025gpt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07513'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'GPT', 'Pretraining Methods']
---
Modern large language foundation models (LLM) have now entered the daily
lives of millions of users. We ask a natural question whether it is possible to
customize LLM for every user or every task. From system and industrial economy
consideration, general continue-training or fine-tuning still require
substantial computation and memory of training GPU nodes, whereas most
inference nodes under deployment, possibly with lower-end GPUs, are configured
to make forward pass fastest possible. We propose a framework to take full
advantages of existing LLMs and systems of online service. We train an
additional branch of transformer blocks on the final-layer embedding of
pretrained LLMs, which is the base, then a carry-on module merge the base
models to compose a customized LLM. We can mix multiple layers, or multiple
LLMs specialized in different domains such as chat, coding, math, to form a new
mixture of LLM that best fit a new task. As the base model don't need to update
parameters, we are able to outsource most computation of the training job on
inference nodes, and only train a lightweight carry-on on training nodes, where
we consume less than 1GB GPU memory to train a 100M carry-on layer on 30B LLM.
We tested Qwen and DeepSeek opensourced models for continue-pretraining and got
faster loss convergence. We use it to improve solving math questions with
extremely small computation and model size, with 1000 data samples of
chain-of-thoughts, and as small as 1 MB parameters of two layer layer carry-on,
and the results are promising.
