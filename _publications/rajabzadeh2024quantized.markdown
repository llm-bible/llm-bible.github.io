---
layout: publication
title: 'Qdylora: Quantized Dynamic Low-rank Adaptation For Efficient Large Language Model Tuning'
authors: Hossein Rajabzadeh, Mojtaba Valipour, Tianshu Zhu, Marzieh Tahaei, Hyock Ju Kwon, Ali Ghodsi, Boxing Chen, Mehdi Rezagholizadeh
conference: "Arxiv"
year: 2024
bibkey: rajabzadeh2024quantized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10462"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Finetuning large language models requires huge GPU memory, restricting the
choice to acquire Larger models. While the quantized version of the Low-Rank
Adaptation technique, named QLoRA, significantly alleviates this issue, finding
the efficient LoRA rank is still challenging. Moreover, QLoRA is trained on a
pre-defined rank and, therefore, cannot be reconfigured for its lower ranks
without requiring further fine-tuning steps. This paper proposes QDyLoRA
-Quantized Dynamic Low-Rank Adaptation-, as an efficient quantization approach
for dynamic low-rank adaptation. Motivated by Dynamic LoRA, QDyLoRA is able to
efficiently finetune LLMs on a set of pre-defined LoRA ranks. QDyLoRA enables
fine-tuning Falcon-40b for ranks 1 to 64 on a single 32 GB V100-GPU through one
round of fine-tuning. Experimental results show that QDyLoRA is competitive to
QLoRA and outperforms when employing its optimal rank.
