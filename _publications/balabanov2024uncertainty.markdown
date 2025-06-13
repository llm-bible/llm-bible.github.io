---
layout: publication
title: 'Uncertainty Quantification In Fine-tuned Llms Using Lora Ensembles'
authors: Oleksandr Balabanov, Hampus Linander
conference: "Arxiv"
year: 2024
bibkey: balabanov2024uncertainty
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.12264'}
tags: ['Merging', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Fine-tuning large language models can improve task specific performance, although a general understanding of what the fine-tuned model has learned, forgotten and how to trust its predictions is still missing. We derive principled uncertainty quantification for fine-tuned LLMs with posterior approximations using computationally efficient low-rank adaptation ensembles. We analyze three common multiple-choice datasets using low-rank adaptation ensembles based on Mistral-7b, and draw quantitative and qualitative conclusions on their perceived complexity and balance between retained prior knowledge and domain specific adaptation during and after fine-tuning. We identify unexpected retention of acquired knowledge during fine-tuning in the overfitting regime.
