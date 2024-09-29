---
layout: publication
title: QFT: Quantized Full-parameter Tuning Of Llms With Affordable Resources
authors: Li Zhikai, Liu Xiaoxuan, Zhu Banghua, Dong Zhen, Gu Qingyi, Keutzer Kurt
conference: "Arxiv"
year: 2023
bibkey: li2023quantized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07147"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have showcased remarkable impacts across a wide spectrum of natural language processing tasks. Fine-tuning these pre-trained models on downstream datasets provides further significant performance gains but this process has been challenging due to its extraordinary resource requirements. To this end existing efforts focus on parameter-efficient fine-tuning which unfortunately fail to capitalize on the powerful potential of full-parameter fine-tuning. In this work we propose QFT a novel Quantized Full-parameter Tuning framework for LLMs that enables memory-efficient fine-tuning without harming performance. Our framework incorporates two novel ideas (i) we adopt the efficient Lion optimizer which only keeps track of the momentum and has consistent update magnitudes for each parameter an inherent advantage for robust quantization; and (ii) we quantize all model states and store them as integer values and present a gradient flow and parameter update scheme for the quantized weights. As a result QFT reduces the model state memory to 2137; of the standard solution while achieving comparable performance e.g. tuning a LLaMA-7B model requires only <30GB of memory satisfied by a single A6000 GPU.
