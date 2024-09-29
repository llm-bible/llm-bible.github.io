---
layout: publication
title: Quantized Side Tuning Fast And Memory45;efficient Tuning Of Quantized Large Language Models
authors: Zhang Zhengxin, Zhao Dan, Miao Xupeng, Oliaro Gabriele, Li Qing, Jiang Yong, Jia Zhihao
conference: "Arxiv"
year: 2024
bibkey: zhang2024quantized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.07159"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
Finetuning large language models (LLMs) has been empirically effective on a variety of downstream tasks. Existing approaches to finetuning an LLM either focus on parameter45;efficient finetuning which only updates a small number of trainable parameters or attempt to reduce the memory footprint during the training phase of the finetuning. Typically the memory footprint during finetuning stems from three contributors model weights optimizer states and intermediate activations. However existing works still require considerable memory and none can simultaneously mitigate memory footprint for all three sources. In this paper we present Quantized Side Tuing (QST) which enables memory45;efficient and fast finetuning of LLMs by operating through a dual45;stage process. First QST quantizes an LLMs model weights into 445;bit to reduce the memory footprint of the LLMs original weights; QST also introduces a side network separated from the LLM which utilizes the hidden states of the LLM to make task45;specific predictions. Using a separate side network avoids performing backpropagation through the LLM thus reducing the memory requirement of the intermediate activations. Furthermore QST leverages several low45;rank adaptors and gradient45;free downsample modules to significantly reduce the trainable parameters so as to save the memory footprint of the optimizer states. Experiments show that QST can reduce the total memory footprint by up to 2.3 × and speed up the finetuning process by up to 3 × while achieving competent performance compared with the state45;of45;the45;art. When it comes to full finetuning QST can reduce the total memory footprint up to 7 ×.
