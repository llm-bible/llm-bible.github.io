---
layout: publication
title: 'Are Large Language Models State-of-the-art Quality Estimators For Machine Translation Of User-generated Content?'
authors: Shenbin Qian, Constantin Orăsan, Diptesh Kanojia, Félix Do Carmo
conference: "Arxiv"
year: 2024
bibkey: qian2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06338"}
tags: ['Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability', 'Prompting', 'Applications', 'In-Context Learning']
---
This paper investigates whether large language models (LLMs) are
state-of-the-art quality estimators for machine translation of user-generated
content (UGC) that contains emotional expressions, without the use of reference
translations. To achieve this, we employ an existing emotion-related dataset
with human-annotated errors and calculate quality evaluation scores based on
the Multi-dimensional Quality Metrics. We compare the accuracy of several LLMs
with that of our fine-tuned baseline models, under in-context learning and
parameter-efficient fine-tuning (PEFT) scenarios. We find that PEFT of LLMs
leads to better performance in score prediction with human interpretable
explanations than fine-tuned models. However, a manual analysis of LLM outputs
reveals that they still have problems such as refusal to reply to a prompt and
unstable output while evaluating machine translation of UGC.
