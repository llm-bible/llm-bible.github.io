---
layout: publication
title: A Comparative Study between Full-Parameter and LoRA-based Fine-Tuning on Chinese Instruction Data for Instruction Following Large Language Model
authors: Sun Xianghui, Ji Yunjie, Ma Baochang, Li Xiangang
conference: "Arxiv"
year: 2023
bibkey: sun2023comparative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08109"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Recently the instruction-tuning of large language models is a crucial area of research in the field of natural language processing. Due to resource and cost limitations several researchers have employed parameter-efficient tuning techniques such as LoRA for instruction tuning and have obtained encouraging results In comparison to full-parameter fine-tuning LoRA-based tuning demonstrates salient benefits in terms of training costs. In this study we undertook experimental comparisons between full-parameter fine-tuning and LoRA-based tuning methods utilizing LLaMA as the base model. The experimental results show that the selection of the foundational model training dataset scale learnable parameter quantity and model training cost are all important factors. We hope that the experimental conclusions of this paper can provide inspiration for training large language models especially in the field of Chinese and help researchers find a better trade-off strategy between training cost and model performance. To facilitate the reproduction of the papers results the dataset model and code will be released.
