---
layout: publication
title: "Revisiting Knowledge Distillation For Autoregressive Language Models"
authors: Zhong Qihuang, Ding Liang, Shen Li, Liu Juhua, Du Bo, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: zhong2024revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11890"}
tags: ['Distillation', 'Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Knowledge distillation (KD) is a common approach to compress a teacher model to reduce its inference cost and memory footprint by training a smaller student model. However in the context of autoregressive language models (LMs) we empirically find that larger teacher LMs might dramatically result in a poorer student. In response to this problem we conduct a series of analyses and reveal that different tokens have different teaching modes neglecting which will lead to performance degradation. Motivated by this we propose a simple yet effective adaptive teaching approach (ATKD) to improve the KD. The core of ATKD is to reduce rote learning and make teaching more diverse and flexible. Extensive experiments on 8 LM tasks show that with the help of ATKD various baseline KD methods can achieve consistent and significant performance gains (up to +3.0437; average score) across all model types and sizes. More encouragingly ATKD can improve the student model generalization effectively.
