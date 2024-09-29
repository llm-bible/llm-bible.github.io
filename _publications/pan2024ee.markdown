---
layout: publication
title: 'Ee-tuning: An Economical Yet Scalable Solution For Tuning Early-exit Large Language Models'
authors: Pan Xuchen, Chen Yanxi, Li Yaliang, Ding Bolin, Zhou Jingren
conference: "Arxiv"
year: 2024
bibkey: pan2024ee
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00518"}
  - {name: "Code", url: "https://github.com/pan-x-c/EE-LLM"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
This work introduces EE-Tuning a lightweight and economical solution to training/tuning early-exit large language models (LLMs). In contrast to the common approach of full-parameter pre-training EE-Tuning augments any pre-trained (and possibly fine-tuned) standard LLM with additional early-exit layers that are tuned in a parameter-efficient manner which requires significantly less computational resources and training data. Our implementation of EE-Tuning achieves outstanding training efficiency via extensive performance optimizations as well as scalability due to its full compatibility with 3D parallelism. Results of systematic experiments validate the efficacy of EE-Tuning confirming that effective early-exit LLM inference can be achieved with a limited training budget. In hope of making early-exit LLMs accessible to the community we release the source code of our implementation of EE-Tuning at https://github.com/pan-x-c/EE-LLM."
