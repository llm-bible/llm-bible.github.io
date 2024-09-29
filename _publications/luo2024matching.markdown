---
layout: publication
title: 'Matching Domain Experts By Training From Scratch On Domain Knowledge'
authors: Luo Xiaoliang, Sun Guangzhi, Love Bradley C.
conference: "Arxiv"
year: 2024
bibkey: luo2024matching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.09395"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Recently large language models (LLMs) have outperformed human experts in predicting the results of neuroscience experiments (Luo et al. 2024). What is the basis for this performance One possibility is that statistical patterns in that specific scientific literature as opposed to emergent reasoning abilities arising from broader training underlie LLMs performance. To evaluate this possibility we trained (next word prediction) a relatively small 124M-parameter GPT-2 model on 1.3 billion tokens of domain-specific knowledge. Despite being orders of magnitude smaller than larger LLMs trained on trillions of tokens small models achieved expert-level performance in predicting neuroscience results. Small models trained on the neuroscience literature succeeded when they were trained from scratch using a tokenizer specifically trained on neuroscience text or when the neuroscience literature was used to finetune a pretrained GPT-2. Our results indicate that expert-level performance may be attained by even small LLMs through domain-specific auto-regressive training approaches.
