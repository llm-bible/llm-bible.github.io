---
layout: publication
title: MSDF A General Open-Domain Multi-Skill Dialog Framework
authors: Zhao Yu, Hu Xinshuo, Li Yunxin, Hu Baotian, Li Dongfang, Chen Sichao, Wang Xiaolong
conference: "Arxiv"
year: 2022
bibkey: zhao2022msdf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.08626"}
tags: ['Applications', 'BERT', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Dialog systems have achieved significant progress and have been widely used in various scenarios. The previous researches mainly focused on designing dialog generation models in a single scenario while comprehensive abilities are required to handle tasks under various scenarios in the real world. In this paper we propose a general Multi-Skill Dialog Framework namely MSDF which can be applied in different dialog tasks (e.g. knowledge grounded dialog and persona based dialog). Specifically we propose a transferable response generator pre-trained on diverse large-scale dialog corpora as the backbone of MSDF consisting of BERT-based encoders and a GPT-based decoder. To select the response consistent with dialog history we propose a consistency selector trained through negative sampling. Moreover the flexible copy mechanism of external knowledge is also employed to enhance the utilization of multiform knowledge in various scenarios. We conduct experiments on knowledge grounded dialog recommendation dialog and persona based dialog tasks. The experimental results indicate that our MSDF outperforms the baseline models with a large margin. In the Multi-skill Dialog of 2021 Language and Intelligence Challenge our general MSDF won the 3rd prize which proves our MSDF is effective and competitive.
