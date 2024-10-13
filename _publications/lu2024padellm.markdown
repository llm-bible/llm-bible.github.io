---
layout: publication
title: 'Padellm-ner: Parallel Decoding In Large Language Models For Named Entity Recognition'
authors: Lu Jinghui, Yang Ziwei, Wang Yanjie, Liu Xuejing, Mac Namee Brian, Huang Can
conference: "Arxiv"
year: 2024
bibkey: lu2024padellm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04838"}
tags: ['GPT', 'Pretraining Methods', 'Tools']
---
In this study, we aim to reduce generation latency for Named Entity
Recognition (NER) with Large Language Models (LLMs). The main cause of high
latency in LLMs is the sequential decoding process, which autoregressively
generates all labels and mentions for NER, significantly increase the sequence
length. To this end, we introduce Parallel Decoding in LLM for NE\}
(PaDeLLM-NER), a approach that integrates seamlessly into existing generative
model frameworks without necessitating additional modules or architectural
modifications. PaDeLLM-NER allows for the simultaneous decoding of all
mentions, thereby reducing generation latency. Experiments reveal that
PaDeLLM-NER significantly increases inference speed that is 1.76 to 10.22 times
faster than the autoregressive approach for both English and Chinese.
Simultaneously it maintains the quality of predictions as evidenced by the
performance that is on par with the state-of-the-art across various datasets.
