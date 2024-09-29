---
layout: publication
title: Task45;agnostic Distillation Of Encoder45;decoder Language Models
authors: Zhang Chen, Yang Yang, Wang Jingang, Song Dawei
conference: "Arxiv"
year: 2023
bibkey: zhang2023task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12330"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Finetuning pretrained language models (LMs) have enabled appealing performance on a diverse array of tasks. The intriguing task45;agnostic property has driven a shifted focus from task45;specific to task45;agnostic distillation of LMs. While task45;agnostic compute45;efficient performance45;preserved LMs can be yielded by task45;agnostic distillation previous studies mainly sit in distillation of either encoder45;only LMs (e.g. BERT) or decoder45;only ones (e.g. GPT) yet largely neglect that distillation of encoder45;decoder LMs (e.g. T5) can posit very distinguished behaviors. Frustratingly we discover that existing task45;agnostic distillation methods can fail to handle the distillation of encoder45;decoder LMs. To the demand we explore a few paths and uncover a path named as MiniEnD that successfully tackles the distillation of encoder45;decoder LMs in a task45;agnostic fashion. We examine MiniEnD on language understanding and abstractive summarization. The results showcase that MiniEnD is generally effective and is competitive compared to other alternatives. We further scale MiniEnD up to distillation of 3B encoder45;decoder language models with interpolated distillation. The results imply the opportunities and challenges in distilling large language models (e.g. LLaMA).
