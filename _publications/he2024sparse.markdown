---
layout: publication
title: 'Sparse Matrix In Large Language Model Fine-tuning'
authors: Haoze He, Juncheng Billy Li, Xuan Jiang, Heather Miller
conference: "Arxiv"
year: 2024
bibkey: he2024sparse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.15525'}
tags: ['Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
LoRA and its variants have become popular parameter-efficient fine-tuning (PEFT) methods due to their ability to avoid excessive computational costs. However, an accuracy gap often exists between PEFT methods and full fine-tuning (FT), and this gap has yet to be systematically studied. In this work, we introduce a method for selecting sparse sub-matrices that aim to minimize the performance gap between PEFT vs. full fine-tuning (FT) while also reducing both fine-tuning computational cost and memory cost. Our Sparse Matrix Tuning (SMT) method begins by identifying the most significant sub-matrices in the gradient update, updating only these blocks during the fine-tuning process. In our experiments, we demonstrate that SMT consistently surpasses other PEFT baseline (e.g. LoRA and DoRA) in fine-tuning popular large language models such as LLaMA across a broad spectrum of tasks, while reducing the GPU memory footprint by 67% compared to FT. We also examine how the performance of LoRA and DoRA tends to plateau and decline as the number of trainable parameters increases, in contrast, our SMT method does not suffer from such issue.
