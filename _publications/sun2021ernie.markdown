---
layout: publication
title: ERNIE 3.0 Large45;scale Knowledge Enhanced Pre45;training For Language Understanding And Generation
authors: Sun Yu, Wang Shuohuan, Feng Shikun, Ding Siyu, Pang Chao, Shang Junyuan, Liu Jiaxiang, Chen Xuyi, Zhao Yanbin, Lu Yuxiang, Liu Weixin, Wu Zhihua, Gong Weibao, Liang Jianzhong, Shang Zhizhou, Sun Peng, Liu Wei, Ouyang Xuan, Yu Dianhai, Tian Hao, Wu Hua, Wang Haifeng
conference: "Arxiv"
year: 2021
bibkey: sun2021ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.02137"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Pre45;trained models have achieved state45;of45;the45;art results in various Natural Language Processing (NLP) tasks. Recent works such as T5 and GPT45;3 have shown that scaling up pre45;trained language models can improve their generalization abilities. Particularly the GPT45;3 model with 175 billion parameters shows its strong task45;agnostic zero45;shot/few45;shot learning capabilities. Despite their success these large45;scale models are trained on plain texts without introducing knowledge such as linguistic knowledge and world knowledge. In addition most large45;scale models are trained in an auto45;regressive way. As a result this kind of traditional fine45;tuning approach demonstrates relatively weak performance when solving downstream language understanding tasks. In order to solve the above problems we propose a unified framework named ERNIE 3.0 for pre45;training large45;scale knowledge enhanced models. It fuses auto45;regressive network and auto45;encoding network so that the trained model can be easily tailored for both natural language understanding and generation tasks with zero45;shot learning few45;shot learning or fine45;tuning. We trained the model with 10 billion parameters on a 4TB corpus consisting of plain texts and a large45;scale knowledge graph. Empirical results show that the model outperforms the state45;of45;the45;art models on 54 Chinese NLP tasks and its English version achieves the first place on the SuperGLUE benchmark (July 3 2021) surpassing the human performance by +0.837; (90.637; vs. 89.837;).
