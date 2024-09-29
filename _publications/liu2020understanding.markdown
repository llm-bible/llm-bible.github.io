---
layout: publication
title: Understanding The Difficulty Of Training Transformers
authors: Liu Liyuan, Liu Xiaodong, Gao Jianfeng, Chen Weizhu, Han Jiawei
conference: "Arxiv"
year: 2020
bibkey: liu2020understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.08249"}
  - {name: "Code", url: "https://github.com/LiyuanLucasLiu/Transforemr&#45;Clinic"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Transformers have proved effective in many NLP tasks. However their training requires non45;trivial efforts regarding designing cutting45;edge optimizers and learning rate schedulers carefully (e.g. conventional SGD fails to train Transformers effectively). Our objective here is to understand textit123;what complicates Transformer training125; from both empirical and theoretical perspectives. Our analysis reveals that unbalanced gradients are not the root cause of the instability of training. Instead we identify an amplification effect that influences training substantially 45;45; for each layer in a multi45;layer Transformer model heavy dependency on its residual branch makes training unstable since it amplifies small parameter perturbations (e.g. parameter updates) and results in significant disturbances in the model output. Yet we observe that a light dependency limits the model potential and leads to inferior trained models. Inspired by our analysis we propose Admin (textbf123;Ad125;aptive textbf123;m125;odel textbf123;in125;itialization) to stabilize stabilize the early stages training and unleash its full potential in the late stage. Extensive experiments show that Admin is more stable converges faster and leads to better performance. Implementations are released at https://github.com/LiyuanLucasLiu/Transforemr&#45;Clinic.
