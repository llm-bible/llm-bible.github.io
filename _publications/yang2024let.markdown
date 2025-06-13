---
layout: publication
title: 'LLM2: Let Large Language Models Harness System 2 Reasoning'
authors: Cheng Yang, Chufan Shi, Siheng Li, Bo Shui, Yujiu Yang, Wai Lam
conference: "Arxiv"
year: 2024
bibkey: yang2024let
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20372"}
tags: ['Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) have exhibited impressive capabilities across a
myriad of tasks, yet they occasionally yield undesirable outputs. We posit that
these limitations are rooted in the foundational autoregressive architecture of
LLMs, which inherently lacks mechanisms for differentiating between desirable
and undesirable results. Drawing inspiration from the dual-process theory of
human cognition, we introduce LLM2, a novel framework that combines an LLM
(System 1) with a process-based verifier (System 2). Within LLM2, the LLM is
responsible for generating plausible candidates, while the verifier provides
timely process-based feedback to distinguish desirable and undesirable outputs.
The verifier is trained with a pairwise comparison loss on synthetic
process-supervision data generated through our token quality exploration
strategy. Empirical results on mathematical reasoning benchmarks substantiate
the efficacy of LLM2, exemplified by an accuracy enhancement from 50.3 to 57.8
(+7.5) for Llama3-1B on GSM8K. Furthermore, when combined with
self-consistency, LLM2 achieves additional improvements, boosting major@20
accuracy from 56.2 to 70.2 (+14.0).
