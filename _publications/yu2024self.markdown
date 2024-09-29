---
layout: publication
title: Siam Self45;improving Code45;assisted Mathematical Reasoning Of Large Language Models
authors: Yu Dian, Peng Baolin, Tian Ye, Song Linfeng, Mi Haitao, Yu Dong
conference: "Arxiv"
year: 2024
bibkey: yu2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15565"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
There is a growing trend of teaching large language models (LLMs) to solve mathematical problems through coding. Existing studies primarily focus on prompting powerful closed45;source models to generate seed training data followed by in45;domain data augmentation equipping LLMs with considerable capabilities for code45;aided mathematical reasoning. However continually training these models on augmented data derived from a few datasets such as GSM8K may impair their generalization abilities and restrict their effectiveness to a narrow range of question types. Conversely the potential of improving such LLMs by leveraging large45;scale expert45;written diverse math question45;answer pairs remains unexplored. To utilize these resources and tackle unique challenges such as code response assessment we propose a novel paradigm that uses a code45;based critic model to guide steps including question45;code data construction quality control and complementary evaluation. We also explore different alignment algorithms with self45;generated instruction/preference data to foster continuous improvement. Experiments across both in45;domain (up to +5.737;) and out45;of45;domain (+4.437;) benchmarks in English and Chinese demonstrate the effectiveness of the proposed paradigm.
