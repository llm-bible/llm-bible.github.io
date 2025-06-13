---
layout: publication
title: 'LM-PUB-QUIZ: A Comprehensive Framework For Zero-shot Evaluation Of Relational Knowledge In Language Models'
authors: Max Ploner, Jacek Wiland, Sebastian Pohl, Alan Akbik
conference: "Arxiv"
year: 2024
bibkey: ploner2024lm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15729"}
tags: ['Transformer', 'Pre-Training', 'Tools', 'Ethics and Bias', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Knowledge probing evaluates the extent to which a language model (LM) has
acquired relational knowledge during its pre-training phase. It provides a
cost-effective means of comparing LMs of different sizes and training setups
and is useful for monitoring knowledge gained or lost during continual learning
(CL). In prior work, we presented an improved knowledge probe called BEAR
(Wiland et al., 2024), which enables the comparison of LMs trained with
different pre-training objectives (causal and masked LMs) and addresses issues
of skewed distributions in previous probes to deliver a more unbiased reading
of LM knowledge. With this paper, we present LM-PUB- QUIZ, a Python framework
and leaderboard built around the BEAR probing mechanism that enables
researchers and practitioners to apply it in their work. It provides options
for standalone evaluation and direct integration into the widely-used training
pipeline of the Hugging Face TRANSFORMERS library. Further, it provides a
fine-grained analysis of different knowledge types to assist users in better
understanding the knowledge in each evaluated LM. We publicly release
LM-PUB-QUIZ as an open-source project.
