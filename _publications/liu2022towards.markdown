---
layout: publication
title: Towards Better Few45;shot And Finetuning Performance With Forgetful Causal Language Models
authors: Liu Hao, Geng Xinyang, Lee Lisa, Mordatch Igor, Levine Sergey, Narang Sharan, Abbeel Pieter
conference: "Arxiv"
year: 2022
bibkey: liu2022towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.13432"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Large language models (LLM) trained using the next45;token45;prediction objective such as GPT3 and PaLM have revolutionized natural language processing in recent years by showing impressive zero45;shot and few45;shot capabilities across a wide range of tasks. In this work we propose a simple technique that significantly boosts the performance of LLMs without adding computational cost. Our key observation is that by performing the next token prediction task with randomly selected past tokens masked out we can improve the quality of the learned representations for downstream language understanding tasks. We hypothesize that randomly masking past tokens prevents over45;attending to recent tokens and encourages attention to tokens in the distant past. We find that our method Forgetful Causal Masking (FCM) significantly improves both few45;shot and finetuning performance of PaLM. We further consider a simple extension T45;FCM which introduces bidirectional context to causal language model without altering the sequence order and further improves finetuning performance.
