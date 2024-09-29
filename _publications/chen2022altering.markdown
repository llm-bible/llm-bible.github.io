---
layout: publication
title: Altclip Altering The Language Encoder In CLIP For Extended Language Capabilities
authors: Chen Zhongzhi, Liu Guang, Zhang Bo-wen, Ye Fulong, Yang Qinghong, Wu Ledell
conference: "Arxiv"
year: 2022
bibkey: chen2022altering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.06679"}
  - {name: "Code", url: "https://github.com/FlagAI&#45;Open/FlagAI"}
tags: ['Has Code', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
In this work we present a conceptually simple and effective method to train a strong bilingual/multilingual multimodal representation model. Starting from the pre45;trained multimodal representation model CLIP released by OpenAI we altered its text encoder with a pre45;trained multilingual text encoder XLM45;R and aligned both languages and image representations by a two45;stage training schema consisting of teacher learning and contrastive learning. We validate our method through evaluations of a wide range of tasks. We set new state45;of45;the45;art performances on a bunch of tasks including ImageNet45;CN Flicker30k45;CN COCO45;CN and XTD. Further we obtain very close performances with CLIP on almost all tasks suggesting that one can simply alter the text encoder in CLIP for extended capabilities such as multilingual understanding. Our models and code are available at https://github.com/FlagAI&#45;Open/FlagAI.
