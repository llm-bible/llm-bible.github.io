---
layout: publication
title: Scala Accelerating Adaptation Of Pre45;trained Transformer45;based Language Models Via Efficient Large45;batch Adversarial Noise
authors: Zhang Minjia, Naresh Niranjan Uma, He Yuxiong
conference: "Arxiv"
year: 2022
bibkey: zhang2022accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.12469"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques', 'Transformer']
---
In recent years large pre45;trained Transformer45;based language models have led to dramatic improvements in many natural language understanding tasks. To train these models with increasing sizes many neural network practitioners attempt to increase the batch sizes in order to leverage multiple GPUs to improve training speed. However increasing the batch size often makes the optimization more difficult leading to slow convergence or poor generalization that can require orders of magnitude more training time to achieve the same model quality. In this paper we explore the steepness of the loss landscape of large45;batch optimization for adapting pre45;trained Transformer45;based language models to domain45;specific tasks and find that it tends to be highly complex and irregular posing challenges to generalization on downstream tasks. To tackle this challenge we propose ScaLA a novel and efficient method to accelerate the adaptation speed of pre45;trained transformer networks. Different from prior methods we take a sequential game45;theoretic approach by adding lightweight adversarial noise into large45;batch optimization which significantly improves adaptation speed while preserving model generalization. Experiment results show that ScaLA attains 2.745;45;9.8× adaptation speedups over the baseline for GLUE on BERT45;base and RoBERTa45;large while achieving comparable and sometimes higher accuracy than the state45;of45;the45;art large45;batch optimization methods. Finally we also address the theoretical aspect of large45;batch optimization with adversarial noise and provide a theoretical convergence rate analysis for ScaLA using techniques for analyzing non45;convex saddle45;point problems.
