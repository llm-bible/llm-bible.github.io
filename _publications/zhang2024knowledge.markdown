---
layout: publication
title: Knowledge Overshadowing Causes Amalgamated Hallucination In Large Language Models
authors: Zhang Yuji, Li Sha, Liu Jiateng, Yu Pengfei, Fung Yi R., Li Jing, Li Manling, Ji Heng
conference: "Arxiv"
year: 2024
bibkey: zhang2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08039"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Hallucination is often regarded as a major impediment for using large language models (LLMs) especially for knowledge45;intensive tasks. Even when the training corpus consists solely of true statements language models still generate hallucinations in the form of amalgamations of multiple facts. We coin this phenomenon as knowledge overshadowing when we query knowledge from a language model with multiple conditions some conditions overshadow others leading to hallucinated outputs. This phenomenon partially stems from training data imbalance which we verify on both pretrained models and fine45;tuned models over a wide range of LM model families and sizes.From a theoretical point of view knowledge overshadowing can be interpreted as over45;generalization of the dominant conditions (patterns). We show that the hallucination rate grows with both the imbalance ratio (between the popular and unpopular condition) and the length of dominant condition description consistent with our derived generalization bound. Finally we propose to utilize overshadowing conditions as a signal to catch hallucination before it is produced along with a training45;free self45;contrastive decoding method to alleviate hallucination during inference. Our proposed approach showcases up to 8237; F1 for hallucination anticipation and 11.237; to 39.437; hallucination control with different models and datasets.
