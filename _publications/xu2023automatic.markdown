---
layout: publication
title: Automatic Pair Construction For Contrastive Post45;training
authors: Xu Canwen, Rosset Corby, Chau Ethan C., Del Corro Luciano, Mahajan Shweti, Mcauley Julian, Neville Jennifer, Awadallah Ahmed Hassan, Rao Nikhil
conference: "Arxiv"
year: 2023
bibkey: xu2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02263"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Alignment serves as an important step to steer large language models (LLMs) towards human preferences. In this paper we propose an automatic way to construct contrastive data for LLM using preference pairs from multiple models of varying strengths (e.g. InstructGPT ChatGPT and GPT45;4). We compare the contrastive techniques of SLiC and DPO to SFT baselines and find that DPO provides a step45;function improvement even after continuing SFT saturates. We also explore a data curriculum learning scheme for contrastive post45;training which starts by learning from easier pairs and transitioning to harder ones which further improves alignment. Finally we scale up our experiments to train with more data and larger models like Orca. Remarkably our automatic contrastive post45;training further improves the performance of Orca already a state45;of45;the45;art instruction learning model tuned with GPT45;4 outputs to outperform ChatGPT.
