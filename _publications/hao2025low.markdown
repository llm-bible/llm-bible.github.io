---
layout: publication
title: 'Low-precision Training Of Large Language Models: Methods, Challenges, And Opportunities'
authors: Zhiwei Hao, Jianyuan Guo, Li Shen, Yong Luo, Han Hu, Guoxia Wang, Dianhai Yu, Yonggang Wen, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: hao2025low
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01043'}
  - {name: "Code", url: 'https://github.com/Hao840/Awesome-Low-Precision-Training'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Survey Paper', 'Reinforcement Learning']
---
Large language models (LLMs) have achieved impressive performance across
various domains. However, the substantial hardware resources required for their
training present a significant barrier to efficiency and scalability. To
mitigate this challenge, low-precision training techniques have been widely
adopted, leading to notable advancements in training efficiency. Despite these
gains, low-precision training involves several components\\(\unicode\{x2013\}\\)such
as weights, activations, and gradients\\(\unicode\{x2013\}\\)each of which can be
represented in different numerical formats. The resulting diversity has created
a fragmented landscape in low-precision training research, making it difficult
for researchers to gain a unified overview of the field. This survey provides a
comprehensive review of existing low-precision training methods. To
systematically organize these approaches, we categorize them into three primary
groups based on their underlying numerical formats, which is a key factor
influencing hardware compatibility, computational efficiency, and ease of
reference for readers. The categories are: (1) fixed-point and integer-based
methods, (2) floating-point-based methods, and (3) customized format-based
methods. Additionally, we discuss quantization-aware training approaches, which
share key similarities with low-precision training during forward propagation.
Finally, we highlight several promising research directions to advance this
field. A collection of papers discussed in this survey is provided in
https://github.com/Hao840/Awesome-Low-Precision-Training.
