---
layout: publication
title: Ee45;tuning An Economical Yet Scalable Solution For Tuning Early45;exit Large Language Models
authors: Pan Xuchen, Chen Yanxi, Li Yaliang, Ding Bolin, Zhou Jingren
conference: "Arxiv"
year: 2024
bibkey: pan2024ee
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00518"}
  - {name: "Code", url: "https://github.com/pan&#45;x&#45;c/EE&#45;LLM"}
tags: ['Efficiency And Optimization', 'Has Code', 'Reinforcement Learning', 'Training Techniques']
---
This work introduces EE45;Tuning a lightweight and economical solution to training/tuning early45;exit large language models (LLMs). In contrast to the common approach of full45;parameter pre45;training EE45;Tuning augments any pre45;trained (and possibly fine45;tuned) standard LLM with additional early45;exit layers that are tuned in a parameter45;efficient manner which requires significantly less computational resources and training data. Our implementation of EE45;Tuning achieves outstanding training efficiency via extensive performance optimizations as well as scalability due to its full compatibility with 3D parallelism. Results of systematic experiments validate the efficacy of EE45;Tuning confirming that effective early45;exit LLM inference can be achieved with a limited training budget. In hope of making early45;exit LLMs accessible to the community we release the source code of our implementation of EE45;Tuning at https://github.com/pan&#45;x&#45;c/EE&#45;LLM.
