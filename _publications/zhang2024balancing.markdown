---
layout: publication
title: Balancing Speciality And Versatility A Coarse To Fine Framework For Supervised Fine45;tuning Large Language Model
authors: Zhang Hengyuan, Wu Yanru, Li Dawei, Yang Sak, Zhao Rui, Jiang Yong, Tan Fei
conference: "Arxiv"
year: 2024
bibkey: zhang2024balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10306"}
  - {name: "Code", url: "https://github.com/rattlesnakey/CoFiTune"}
tags: ['Applications', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Aligned Large Language Models (LLMs) showcase remarkable versatility capable of handling diverse real45;world tasks. Meanwhile aligned LLMs are also expected to exhibit speciality excelling in specific applications. However fine45;tuning with extra data a common practice to gain speciality often leads to catastrophic forgetting (CF) of previously acquired versatility hindering the models performance across diverse tasks. In response to this challenge we propose CoFiTune a coarse to fine framework in an attempt to strike the balance between speciality and versatility. At the coarse45;grained level an empirical tree45;search algorithm is utilized to pinpoint and update specific modules that are crucial for speciality while keeping other parameters frozen; at the fine45;grained level a soft45;masking mechanism regulates the update to the LLMs mitigating the CF issue without harming speciality. In an overall evaluation of both speciality and versatility CoFiTune consistently outperforms baseline methods across diverse tasks and model scales. Compared to the full45;parameter SFT CoFiTune leads to about 1437; versatility improvement and marginal speciality loss on a 13B model. Lastly based on further analysis we provide a speculative insight into the information forwarding process in LLMs which helps explain the effectiveness of the proposed method. The code is available at https://github.com/rattlesnakey/CoFiTune.
