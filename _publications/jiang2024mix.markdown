---
layout: publication
title: Mix45;cpt A Domain Adaptation Framework Via Decoupling Knowledge Learning And Format Alignment
authors: Jiang Jinhao, Li Junyi, Zhao Wayne Xin, Song Yang, Zhang Tao, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: jiang2024mix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10804"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'RAG', 'Tools', 'Training Techniques']
---
Adapting general large language models (LLMs) to specialized domains presents great challenges due to varied data distributions. This adaptation typically requires continual pre45;training on massive domain45;specific corpora to facilitate knowledge memorization followed by training to apply this knowledge following human instructions and preferences. However this method may result in inefficient knowledge memorization due to a lack of awareness of knowledge utilization and imposes substantial demands on LLMs to simultaneously learn knowledge utilization and format alignment with limited training samples. To facilitate the domain adaptation of LLM we revise this process and propose a new domain adaptation framework including domain knowledge learning and general format alignment called Mix45;CPT. Specifically we first conduct a knowledge mixture continual pre45;training that concurrently focuses on knowledge memorization and utilization allowing for mutual reinforcement. To avoid catastrophic forgetting during the continual pre45;training process we further incorporate a logit swap self45;distillation constraint. Subsequently leveraging the knowledge and capabilities acquired during continual pre45;training we efficiently perform instruction tuning and alignment with a few general training samples to achieve format alignment. Extensive experiments demonstrate that our proposed Mix45;CPT framework can simultaneously improve the task45;solving capabilities of LLMs on the target and general domains compared to the traditional adaptation methods.
