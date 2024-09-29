---
layout: publication
title: Textboost Towards One45;shot Personalization Of Text45;to45;image Models Via Fine45;tuning Text Encoder
authors: Park Nahyeon, Kim Kunhee, Shim Hyunjung
conference: "Arxiv"
year: 2024
bibkey: park2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08248"}
tags: ['Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recent breakthroughs in text45;to45;image models have opened up promising research avenues in personalized image generation enabling users to create diverse images of a specific subject using natural language prompts. However existing methods often suffer from performance degradation when given only a single reference image. They tend to overfit the input producing highly similar outputs regardless of the text prompt. This paper addresses the challenge of one45;shot personalization by mitigating overfitting enabling the creation of controllable images through text prompts. Specifically we propose a selective fine45;tuning strategy that focuses on the text encoder. Furthermore we introduce three key techniques to enhance personalization performance (1) augmentation tokens to encourage feature disentanglement and alleviate overfitting (2) a knowledge45;preservation loss to reduce language drift and promote generalizability across diverse prompts and (3) SNR45;weighted sampling for efficient training. Extensive experiments demonstrate that our approach efficiently generates high45;quality diverse images using only a single reference image while significantly reducing memory and storage requirements.
