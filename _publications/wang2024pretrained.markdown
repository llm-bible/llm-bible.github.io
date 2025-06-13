---
layout: publication
title: 'PMSS: Pretrained Matrices Skeleton Selection For LLM Fine-tuning'
authors: Qibin Wang, Xiaolin Hu, Weikai Xu, Wei Liu, Jian Luan, Bin Wang
conference: "Arxiv"
year: 2024
bibkey: wang2024pretrained
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.16722'}
tags: ['RAG', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Low-rank adaptation (LoRA) and its variants have recently gained much
interest due to their ability to avoid excessive inference costs. However, LoRA
still encounters the following challenges: (1) Limitation of low-rank
assumption; and (2) Its initialization method may be suboptimal. To this end,
we propose PMSS(Pre-trained Matrices Skeleton Selection), which enables
high-rank updates with low costs while leveraging semantic and linguistic
information inherent in pre-trained weight. It achieves this by selecting
skeletons from the pre-trained weight matrix and only learning a small matrix
instead. Experiments demonstrate that PMSS outperforms LoRA and other
fine-tuning methods across tasks with much less trainable parameters. We
demonstrate its effectiveness, especially in handling complex tasks such as
DROP benchmark(+3.4%/+5.9% on LLaMA2-7B/13B) and math
reasoning(+12.89%/+5.61%/+3.11% on LLaMA2-7B, Mistral-7B and Gemma-7B of
GSM8K). The code and model will be released soon.
