---
layout: publication
title: 'Increasing Model Capacity For Free: A Simple Strategy For Parameter Efficient Fine-tuning'
authors: Haobo Song, Hao Zhao, Soumajit Majumder, Tao Lin
conference: "Arxiv"
year: 2024
bibkey: song2024increasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01320"}
  - {name: "Code", url: "https://github.com/LINs-lab/CapaBoost"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Fine-tuning large pre-trained foundation models, such as the 175B GPT-3, has
attracted more attention for downstream tasks recently. While
parameter-efficient fine-tuning methods have been proposed and proven effective
without retraining all model parameters, their performance is limited by the
capacity of incremental modules, especially under constrained parameter
budgets. \\ To overcome this challenge, we propose CapaBoost, a simple yet
effective strategy that enhances model capacity by leveraging low-rank updates
through parallel weight modules in target layers. By applying static random
masks to the shared weight matrix, CapaBoost constructs a diverse set of weight
matrices, effectively increasing the rank of incremental weights without adding
parameters. Notably, our approach can be seamlessly integrated into various
existing parameter-efficient fine-tuning methods. We extensively validate the
efficacy of CapaBoost through experiments on diverse downstream tasks,
including natural language understanding, question answering, and image
classification. Our results demonstrate significant improvements over
baselines, without incurring additional computation or storage costs. Our code
is available at \url\{https://github.com/LINs-lab/CapaBoost\}.
