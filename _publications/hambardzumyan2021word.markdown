---
layout: publication
title: WARP Word45;level Adversarial Reprogramming
authors: Hambardzumyan Karen, Khachatrian Hrant, May Jonathan
conference: "Arxiv"
year: 2021
bibkey: hambardzumyan2021word
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.00121"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Transfer learning from pretrained language models recently became the dominant approach for solving many NLP tasks. A common approach to transfer learning for multiple tasks that maximize parameter sharing trains one or more task45;specific layers on top of the language model. In this paper we present an alternative approach based on adversarial reprogramming which extends earlier work on automatic prompt generation. Adversarial reprogramming attempts to learn task45;specific word embeddings that when concatenated to the input text instruct the language model to solve the specified task. Using up to 25K trainable parameters per task this approach outperforms all existing methods with up to 25M trainable parameters on the public leaderboard of the GLUE benchmark. Our method initialized with task45;specific human45;readable prompts also works in a few45;shot setting outperforming GPT45;3 on two SuperGLUE tasks with just 32 training samples.
