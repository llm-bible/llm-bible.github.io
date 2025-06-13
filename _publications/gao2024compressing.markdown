---
layout: publication
title: 'Selfcp: Compressing Over-limit Prompt Via The Frozen Large Language Model Itself'
authors: Jun Gao, Ziqiang Cao, Wenjie Li
conference: "Arxiv"
year: 2024
bibkey: gao2024compressing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17052"}
tags: ['Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Long prompt leads to huge hardware costs when using transformer-based Large
Language Models (LLMs). Unfortunately, many tasks, such as summarization,
inevitably introduce long documents, and the wide application of in-context
learning easily makes the prompt length explode. This paper proposes a
Self-Compressor (SelfCP), which employs the target LLM itself to compress
over-limit prompts into dense vectors while keeping the allowed prompts
unmodified. Dense vectors are then projected into dense tokens via a learnable
connector to make the same LLM unburden to understand. The connector is
supervised-tuned under the language modeling objective of the LLM on relatively
long texts selected from publicly accessed datasets, involving an instruction
dataset to make SelfCP respond to various prompts, while the target LLM keeps
frozen during training. We build the lightweight SelfCP upon 2 different
backbones with merely 17M learnable parameters originating from the connector
and a learnable embedding. Evaluation on both English and Chinese benchmarks
demonstrate that SelfCP effectively substitutes 12\\(\times\\) over-limit prompts
with dense tokens to reduce memory costs and booster inference throughputs, yet
improving response quality. The outstanding performance brings an efficient
solution for LLMs to tackle long prompts without training LLMs from scratch.
