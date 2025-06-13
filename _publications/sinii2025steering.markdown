---
layout: publication
title: 'Steering LLM Reasoning Through Bias-only Adaptation'
authors: Viacheslav Sinii, Alexey Gorbatovski, Artem Cherepanov, Boris Shaposhnikov, Nikita Balagansky, Daniil Gavrilov
conference: "Arxiv"
year: 2025
bibkey: sinii2025steering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18706"}
tags: ['Ethics and Bias', 'Training Techniques', 'Reinforcement Learning']
---
Recent work on reasoning-oriented language models, exemplified by o1-like systems, suggests that reinforcement-learning (RL) finetuning does not create new capabilities but instead strengthens reasoning patterns already latent in the pretrained network. We test this claim by training steering vectors: layer-wise biases that additively amplify selected hidden features while leaving all original weights unchanged. Experiments on four base models across the GSM8K and MATH benchmarks show that steering vectors recover, and in several cases exceed, the accuracy of fully-tuned counterparts. This result supports the view that the required reasoning skills pre-exist in the base model. Further, logit-lens analysis reveals that the trained vectors consistently boost token groups linked to structured languages and logical connectors, providing an interpretable account that aligns with the demands of quantitative reasoning tasks.
