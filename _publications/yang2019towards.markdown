---
layout: publication
title: Towards Making The Most Of BERT In Neural Machine Translation
authors: Yang Jiacheng, Wang Mingxuan, Zhou Hao, Zhao Chengqi, Yu Yong, Zhang Weinan, Li Lei
conference: "Arxiv"
year: 2019
bibkey: yang2019towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1908.05672"}
  - {name: "Code", url: "https://github.com/bytedance/neurst/"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
GPT45;2 and BERT demonstrate the effectiveness of using pre45;trained language models (LMs) on various natural language processing tasks. However LM fine45;tuning often suffers from catastrophic forgetting when applied to resource45;rich tasks. In this work we introduce a concerted training framework (CTNMT) that is the key to integrate the pre45;trained LMs to neural machine translation (NMT). Our proposed CTNMT consists of three techniques a) asymptotic distillation to ensure that the NMT model can retain the previous pre45;trained knowledge; b) a dynamic switching gate to avoid catastrophic forgetting of pre45;trained knowledge; and c) a strategy to adjust the learning paces according to a scheduled policy. Our experiments in machine translation show CTNMT gains of up to 3 BLEU score on the WMT14 English45;German language pair which even surpasses the previous state45;of45;the45;art pre45;training aided NMT by 1.4 BLEU score. While for the large WMT14 English45;French task with 40 millions of sentence45;pairs our base model still significantly improves upon the state45;of45;the45;art Transformer big model by more than 1 BLEU score. The code and model can be downloaded from https://github.com/bytedance/neurst/ tree/master/examples/ctnmt.
