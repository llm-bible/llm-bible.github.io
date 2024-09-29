---
layout: publication
title: Pneumollm Harnessing The Power Of Large Language Model For Pneumoconiosis Diagnosis
authors: Song Meiyue, Yu Zhihua, Wang Jiaxin, Wang Jiarui, Lu Yuting, Li Baicun, Wang Xiaoxu, Huang Qinghua, Li Zhijun, Kanellakis Nikolaos I., Liu Jiangfeng, Wang Jing, Wang Binglu, Yang Juntao
conference: "Arxiv"
year: 2023
bibkey: song2023harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.03490"}
  - {name: "Code", url: "https://github.com/CodeMonsterPHD/PneumoLLM/tree/main"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The conventional pretraining45;and45;finetuning paradigm while effective for common diseases with ample data faces challenges in diagnosing data45;scarce occupational diseases like pneumoconiosis. Recently large language models (LLMs) have exhibits unprecedented ability when conducting multiple tasks in dialogue bringing opportunities to diagnosis. A common strategy might involve using adapter layers for vision45;language alignment and diagnosis in a dialogic manner. Yet this approach often requires optimization of extensive learnable parameters in the text branch and the dialogue head potentially diminishing the LLMs efficacy especially with limited training data. In our work we innovate by eliminating the text branch and substituting the dialogue head with a classification head. This approach presents a more effective method for harnessing LLMs in diagnosis with fewer learnable parameters. Furthermore to balance the retention of detailed image information with progression towards accurate diagnosis we introduce the contextual multi45;token engine. This engine is specialized in adaptively generating diagnostic tokens. Additionally we propose the information emitter module which unidirectionally emits information from image tokens to diagnosis tokens. Comprehensive experiments validate the superiority of our methods and the effectiveness of proposed modules. Our codes can be found at https://github.com/CodeMonsterPHD/PneumoLLM/tree/main.
