---
layout: publication
title: Melora\: Mini-ensemble Low-rank Adapters For Parameter-efficient Fine-tuning
authors: Ren Pengjie, Shi Chengshun, Wu Shiguang, Zhang Mengqi, Ren Zhaochun, De Rijke Maarten, Chen Zhumin, Pei Jiahuan
conference: "Arxiv"
year: 2024
bibkey: ren2024mini
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17263"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Parameter-efficient fine-tuning (PEFT) is a popular method for tailoring pre-trained large language models (LLMs) especially as the models scale and the diversity of tasks increase. Low-rank adaptation (LoRA) is based on the idea that the adaptation process is intrinsically low-dimensional i.e. significant model changes can be represented with relatively few parameters. However decreasing the rank encounters challenges with generalization errors for specific tasks when compared to full-parameter fine-tuning. We present MELoRA a mini-ensemble low-rank adapters that uses fewer trainable parameters while maintaining a higher rank thereby offering improved performance potential. The core idea is to freeze original pretrained weights and train a group of mini LoRAs with only a small number of parameters. This can capture a significant degree of diversity among mini LoRAs thus promoting better generalization ability. We conduct a theoretical analysis and empirical studies on various NLP tasks. Our experimental results show that compared to LoRA MELoRA achieves better performance with 8 times fewer trainable parameters on natural language understanding tasks and 36 times fewer trainable parameters on instruction following tasks which demonstrates the effectiveness of MELoRA.
