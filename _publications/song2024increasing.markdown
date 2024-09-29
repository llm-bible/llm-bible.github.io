---
layout: publication
title: Increasing Model Capacity For Free A Simple Strategy For Parameter Efficient Fine45;tuning
authors: Song Haobo, Zhao Hao, Majumder Soumajit, Lin Tao
conference: "Arxiv"
year: 2024
bibkey: song2024increasing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01320"}
  - {name: "Code", url: "https://github.com/LINs&#45;lab/CapaBoost&#125;"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Fine45;tuning large pre45;trained foundation models such as the 175B GPT45;3 has attracted more attention for downstream tasks recently. While parameter45;efficient fine45;tuning methods have been proposed and proven effective without retraining all model parameters their performance is limited by the capacity of incremental modules especially under constrained parameter budgets. To overcome this challenge we propose CapaBoost a simple yet effective strategy that enhances model capacity by leveraging low45;rank updates through parallel weight modules in target layers. By applying static random masks to the shared weight matrix CapaBoost constructs a diverse set of weight matrices effectively increasing the rank of incremental weights without adding parameters. Notably our approach can be seamlessly integrated into various existing parameter45;efficient fine45;tuning methods. We extensively validate the efficacy of CapaBoost through experiments on diverse downstream tasks including natural language understanding question answering and image classification. Our results demonstrate significant improvements over baselines without incurring additional computation or storage costs. Our code is available at url123;https://github.com/LINs&#45;lab/CapaBoost&#125;.
