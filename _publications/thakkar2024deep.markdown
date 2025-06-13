---
layout: publication
title: 'A Deep Dive Into The Trade-offs Of Parameter-efficient Preference Alignment Techniques'
authors: Megh Thakkar, Quentin Fournier, Matthew D Riemer, Pin-yu Chen, Amal Zouaq, Payel Das, Sarath Chandar
conference: "Arxiv"
year: 2024
bibkey: thakkar2024deep
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.04879'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large language models are first pre-trained on trillions of tokens and then
instruction-tuned or aligned to specific preferences. While pre-training
remains out of reach for most researchers due to the compute required,
fine-tuning has become affordable thanks to parameter-efficient methods such as
LoRA and QLoRA. Alignment is known to be sensitive to the many factors
involved, including the quantity and quality of data, the alignment method, and
the adapter rank. However, there has not yet been an extensive study of their
effect on downstream performance. To address this gap, we conduct an in-depth
investigation of the impact of popular choices for three crucial axes: (i) the
alignment dataset (HH-RLHF and BeaverTails), (ii) the alignment technique (SFT
and DPO), and (iii) the model (LLaMA-1, Vicuna-v1.3, Mistral-7b, and
Mistral-7b-Instruct). Our extensive setup spanning over 300 experiments reveals
consistent trends and unexpected findings. We observe how more informative data
helps with preference alignment, cases where supervised fine-tuning outperforms
preference optimization, and how aligning to a distinct preference boosts
performance on downstream tasks. Through our in-depth analyses, we put forward
key guidelines to help researchers perform more effective parameter-efficient
LLM alignment.
