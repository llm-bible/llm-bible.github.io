---
layout: publication
title: 'Pretrained Llms Learn Multiple Types Of Uncertainty'
authors: Roi Cohen, Omri Fahn, Gerard De Melo
conference: "Arxiv"
year: 2025
bibkey: cohen2025pretrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21218"}
tags: ['Training Techniques', 'Scaling Laws', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Large Language Models are known to capture real-world knowledge, allowing them to excel in many downstream tasks. Despite recent advances, these models are still prone to what are commonly known as hallucinations, causing them to emit unwanted and factually incorrect text. In this work, we study how well LLMs capture uncertainty, without explicitly being trained for that. We show that, if considering uncertainty as a linear concept in the model's latent space, it might indeed be captured, even after only pretraining. We further show that, though unintuitive, LLMs appear to capture several different types of uncertainty, each of which can be useful to predict the correctness for a specific task or benchmark. Furthermore, we provide in-depth results such as demonstrating a correlation between our correction prediction and the model's ability to abstain from misinformation using words, and the lack of impact of model scaling for capturing uncertainty. Finally, we claim that unifying the uncertainty types as a single one using instruction-tuning or [IDK]-token tuning is helpful for the model in terms of correctness prediction.
