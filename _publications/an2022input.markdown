---
layout: publication
title: Input45;tuning Adapting Unfamiliar Inputs To Frozen Pretrained Models
authors: An Shengnan, Li Yifei, Lin Zeqi, Liu Qian, Chen Bei, Fu Qiang, Chen Weizhu, Zheng Nanning, Lou Jian-guang
conference: "Arxiv"
year: 2022
bibkey: an2022input
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.03131"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Recently the prompt45;tuning paradigm has attracted significant attention. By only tuning continuous prompts with a frozen pre45;trained language model (PLM) prompt45;tuning takes a step towards deploying a shared frozen PLM to serve numerous downstream tasks. Although prompt45;tuning shows good performance on certain natural language understanding (NLU) tasks its effectiveness on natural language generation (NLG) tasks is still under45;explored. In this paper we argue that one of the factors hindering the development of prompt45;tuning on NLG tasks is the unfamiliar inputs (i.e. inputs are linguistically different from the pretraining corpus). For example our preliminary exploration reveals a large performance gap between prompt45;tuning and fine45;tuning when unfamiliar inputs occur frequently in NLG tasks. This motivates us to propose input45;tuning which fine45;tunes both the continuous prompts and the input representations leading to a more effective way to adapt unfamiliar inputs to frozen PLMs. Our proposed input45;tuning is conceptually simple and empirically powerful. Experimental results on seven NLG tasks demonstrate that input45;tuning is significantly and consistently better than prompt45;tuning. Furthermore on three of these tasks input45;tuning can achieve a comparable or even better performance than fine45;tuning.
