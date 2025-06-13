---
layout: publication
title: 'SEAL: Safety-enhanced Aligned LLM Fine-tuning Via Bilevel Data Selection'
authors: Han Shen, Pin-yu Chen, Payel Das, Tianyi Chen
conference: "Arxiv"
year: 2024
bibkey: shen2024safety
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07471"}
  - {name: "Code", url: "https://github.com/hanshen95/SEAL"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Fine-tuning on task-specific data to boost downstream performance is a
crucial step for leveraging Large Language Models (LLMs). However, previous
studies have demonstrated that fine-tuning the models on several adversarial
samples or even benign data can greatly comprise the model's pre-equipped
alignment and safety capabilities. In this work, we propose SEAL, a novel
framework to enhance safety in LLM fine-tuning. SEAL learns a data ranker based
on the bilevel optimization to up rank the safe and high-quality fine-tuning
data and down rank the unsafe or low-quality ones. Models trained with SEAL
demonstrate superior quality over multiple baselines, with 8.5% and 9.7% win
rate increase compared to random selection respectively on Llama-3-8b-Instruct
and Merlinite-7b models. Our code is available on github
https://github.com/hanshen95/SEAL.
