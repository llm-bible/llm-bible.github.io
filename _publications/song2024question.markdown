---
layout: publication
title: Moviechat+: Question-aware Sparse Memory For Long Video Question Answering
authors: Song Enxin, Chai Wenhao, Ye Tian, Hwang Jenq-neng, Li Xi, Wang Gaoang
conference: "Arxiv"
year: 2024
bibkey: song2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17176"}
  - {name: "Code", url: "https://github.com/rese1f/MovieChat"}
tags: ['Applications', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Recently integrating video foundation models and large language models to build a video understanding system can overcome the limitations of specific pre-defined vision tasks. Yet existing methods either employ complex spatial-temporal modules or rely heavily on additional perception models to extract temporal features for video understanding and they only perform well on short videos. For long videos the computational complexity and memory costs associated with long-term temporal connections are significantly increased posing additional challenges.Taking advantage of the Atkinson-Shiffrin memory model with tokens in Transformers being employed as the carriers of memory in combination with our specially designed memory mechanism we propose MovieChat to overcome these challenges. We lift pre-trained multi-modal large language models for understanding long videos without incorporating additional trainable temporal modules employing a zero-shot approach. MovieChat achieves state-of-the-art performance in long video understanding along with the released MovieChat-1K benchmark with 1K long video 2K temporal grounding labels and 14K manual annotations for validation of the effectiveness of our method. The code along with the dataset can be accessed via the following https://github.com/rese1f/MovieChat."
