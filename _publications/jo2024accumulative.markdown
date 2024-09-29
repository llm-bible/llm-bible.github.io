---
layout: publication
title: 'A2SF: Accumulative Attention Scoring With Forgetting Factor For Token Pruning In Transformer Decoder'
authors: Jo Hyun-rae, Shin Dongkun
conference: "Arxiv"
year: 2024
bibkey: jo2024accumulative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20485"}
tags: ['Attention Mechanism', 'Bias Mitigation', 'Efficiency And Optimization', 'Ethics And Bias', 'Fairness', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Transformer']
---
Recently large language models (LLM) based on transformers are facing memory bottleneck issues due to KV cache especially in long sequence handling. Previous researches proposed KV cache compression techniques that identify insignificant tokens based on Accumulative Attention Scores and removes their items from KV cache noting that only few tokens play an important role in attention operations. However we have observed that the existing Accumulative Attention Score is not suitable for the transformer decoder structure. In the decoder model the number of times the Attention Score accumulates varies depending on the order of token appearance due to the effect of masking causing an uneven comparison between tokens. To solve this we propose Accumulative Attention Score with Forgetting Factor (A2SF) technique which introduces a Forgetting Factor in the Attention Score accumulation process. A2SF applies a penalty to the past Attention Score generated from old tokens by repeatedly multiplying the Forgetting Factor to the Attention Score over time. Therefore older tokens receive a larger penalty providing fairness among different ages of tokens. Through the fair comparison among tokens we can more effectively select important tokens. We have verified the accuracy improvement through A2SF in the OPT and LLaMA models and A2SF improves the accuracy of LLaMA 2 by up to 7.837; and 5.137; on 1-shot and 0-shot.
