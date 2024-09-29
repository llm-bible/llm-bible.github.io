---
layout: publication
title: Accelerating Pre45;training Of Multimodal Llms Via Chain45;of45;sight
authors: Huang Ziyuan, Ji Kaixiang, Gong Biao, Qing Zhiwu, Zhang Qinglong, Zheng Kecheng, Wang Jian, Chen Jingdong, Yang Ming
conference: "Arxiv"
year: 2024
bibkey: huang2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15819"}
tags: ['Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
This paper introduces Chain45;of45;Sight a vision45;language bridge module that accelerates the pre45;training of Multimodal Large Language Models (MLLMs). Our approach employs a sequence of visual resamplers that capture visual details at various spacial scales. This architecture not only leverages global and local visual contexts effectively but also facilitates the flexible extension of visual tokens through a compound token scaling strategy allowing up to a 16x increase in the token count post pre45;training. Consequently Chain45;of45;Sight requires significantly fewer visual tokens in the pre45;training phase compared to the fine45;tuning phase. This intentional reduction of visual tokens during pre45;training notably accelerates the pre45;training process cutting down the wall45;clock training time by ~7337;. Empirical results on a series of vision45;language benchmarks reveal that the pre45;train acceleration through Chain45;of45;Sight is achieved without sacrificing performance matching or surpassing the standard pipeline of utilizing all visual tokens throughout the entire training process. Further scaling up the number of visual tokens for pre45;training leads to stronger performances competitive to existing approaches in a series of benchmarks.
