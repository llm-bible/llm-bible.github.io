---
layout: publication
title: Mitigating Large Language Model Hallucination With Faithful Finetuning
authors: Hu Minda, He Bowei, Wang Yufei, Li Liangyou, Ma Chen, King Irwin
conference: "Arxiv"
year: 2024
bibkey: hu2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11267"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) have demonstrated remarkable performance on various natural language processing tasks. However they are prone to generating fluent yet untruthful responses known as hallucinations. Hallucinations can lead to the spread of misinformation and cause harm in critical applications. Mitigating hallucinations is challenging as they arise from factors such as noisy data model overconfidence lack of knowledge and the generation process itself. Recent efforts have attempted to address this issue through representation editing and decoding algorithms reducing hallucinations without major structural changes or retraining. However these approaches either implicitly edit LLMs behavior in latent space or suppress the tendency to output unfaithful results during decoding instead of explicitly modeling on hallucination. In this work we introduce Faithful Finetuning (F2) a novel method that explicitly models the process of faithful question answering through carefully designed loss functions during fine-tuning. We conduct extensive experiments on popular datasets and demonstrate that F2 achieves significant improvements over vanilla models and baselines.
