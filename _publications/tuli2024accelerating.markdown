---
layout: publication
title: 'Dynamo: Accelerating Language Model Inference With Dynamic Multi-token Sampling'
authors: Shikhar Tuli, Chi-heng Lin, Yen-chang Hsu, Niraj K. Jha, Yilin Shen, Hongxia Jin
conference: "Arxiv"
year: 2024
bibkey: tuli2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00888"}
tags: ['Training Techniques', 'Tools', 'Language Modeling', 'RAG', 'GPT', 'Pretraining Methods', 'Applications']
---
Traditional language models operate autoregressively, i.e., they predict one
token at a time. Rapid explosion in model sizes has resulted in high inference
times. In this work, we propose DynaMo, a suite of multi-token prediction
language models that reduce net inference times. Our models
\\(\textit\{dynamically\}\\) predict multiple tokens based on their confidence in the
predicted joint probability distribution. We propose a lightweight technique to
train these models, leveraging the weights of traditional autoregressive
counterparts. Moreover, we propose novel ways to enhance the estimated joint
probability to improve text generation quality, namely co-occurrence weighted
masking and adaptive thresholding. We also propose systematic qualitative and
quantitative methods to rigorously test the quality of generated text for
non-autoregressive generation. One of the models in our suite, DynaMo-7.3B-T3,
achieves same-quality generated text as the baseline (Pythia-6.9B) while
achieving 2.57\\(\times\\) speed-up with only 5.87% and 2.67% parameter and
training time overheads, respectively.
