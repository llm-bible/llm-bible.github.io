---
layout: publication
title: 'Learning To Compress Prompts With Gist Tokens'
authors: Mu Jesse, Li Xiang Lisa, Goodman Noah
conference: "Arxiv"
year: 2023
bibkey: mu2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08467"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques', 'Transformer']
---
"Prompting is the primary way to utilize the multitask capabilities of language models (LMs), but prompts occupy valuable space in the input context window, and repeatedly encoding the same prompt is computationally inefficient. Finetuning and distillation methods allow for specialization of LMs without prompting, but require retraining the model for each task. To avoid this trade-off entirely, we present gisting, which trains an LM to compress prompts into smaller sets of gist tokens which can be cached and reused for compute efficiency. Gist models can be trained with no additional cost over standard instruction finetuning by simply modifying Transformer attention masks to encourage prompt compression. On decoder (LLaMA-7B) and encoder-decoder (FLAN-T5-XXL) LMs, gisting enables up to 26x compression of prompts, resulting in up to 40&#37; FLOPs reductions, 4.2&#37; wall time speedups, and storage savings, all with minimal loss in output quality."
