---
layout: publication
title: $VILA^2$&#58; VILA Augmented VILA
authors: Fang Yunhao, Zhu Ligeng, Lu Yao, Wang Yan, Molchanov Pavlo, Cho Jang Hyun, Pavone Marco, Han Song, Yin Hongxu
conference: "Arxiv"
year: 2024
bibkey: fang2024vila
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17453"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Visual language models (VLMs) have rapidly progressed driven by the success of large language models (LLMs). While model architectures and training infrastructures advance rapidly data curation remains under-explored. When data quantity and quality become a bottleneck existing work either directly crawls more raw data from the Internet that does not have a guarantee of data quality or distills from black-box commercial models (e.g. GPT-4V / Gemini) causing the performance upper bounded by that model. In this work we introduce a novel approach that includes a self-augment step and a specialist-augment step to iteratively improve data quality and model performance. In the self-augment step a VLM recaptions its own pretraining data to enhance data quality and then retrains from scratch using this refined dataset to improve model performance. This process can iterate for several rounds. Once self-augmentation saturates we employ several specialist VLMs finetuned from the self-augmented VLM with domain-specific expertise to further infuse specialist knowledge into the generalist VLM through task-oriented recaptioning and retraining. With the combined self-augmented and specialist-augmented training we introduce VILA^2 (VILA-augmented-VILA) a VLM family that consistently improves the accuracy on a wide range of tasks over prior art and achieves new state-of-the-art results on MMMU leaderboard among open-sourced models.
