---
layout: publication
title: VILA^2 VILA Augmented VILA
authors: Fang Yunhao, Zhu Ligeng, Lu Yao, Wang Yan, Molchanov Pavlo, Cho Jang Hyun, Pavone Marco, Han Song, Yin Hongxu
conference: "Arxiv"
year: 2024
bibkey: fang2024vila
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17453"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Visual language models (VLMs) have rapidly progressed driven by the success of large language models (LLMs). While model architectures and training infrastructures advance rapidly data curation remains under45;explored. When data quantity and quality become a bottleneck existing work either directly crawls more raw data from the Internet that does not have a guarantee of data quality or distills from black45;box commercial models (e.g. GPT45;4V / Gemini) causing the performance upper bounded by that model. In this work we introduce a novel approach that includes a self45;augment step and a specialist45;augment step to iteratively improve data quality and model performance. In the self45;augment step a VLM recaptions its own pretraining data to enhance data quality and then retrains from scratch using this refined dataset to improve model performance. This process can iterate for several rounds. Once self45;augmentation saturates we employ several specialist VLMs finetuned from the self45;augmented VLM with domain45;specific expertise to further infuse specialist knowledge into the generalist VLM through task45;oriented recaptioning and retraining. With the combined self45;augmented and specialist45;augmented training we introduce VILA^2 (VILA45;augmented45;VILA) a VLM family that consistently improves the accuracy on a wide range of tasks over prior art and achieves new state45;of45;the45;art results on MMMU leaderboard among open45;sourced models.
