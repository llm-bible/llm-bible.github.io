---
layout: publication
title: Fl45;tuning Layer Tuning For Feed45;forward Network In Transformer
authors: Liu Jingping, Song Yuqiu, Xue Kui, Sun Hongli, Wang Chao, Chen Lihan, Jiang Haiyun, Liang Jiaqing, Ruan Tong
conference: "Arxiv"
year: 2022
bibkey: liu2022fl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.15312"}
  - {name: "Code", url: "https://github.com/genggui001/FL&#45;Tuning"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Prompt tuning is an emerging way of adapting pre45;trained language models to downstream tasks. However the existing studies are mainly to add prompts to the input sequence. This way would not work as expected due to the intermediate multi45;head self45;attention and feed45;forward network computation making model optimization not very smooth. Hence we propose a novel tuning way called layer tuning aiming to add learnable parameters in Transformer layers. Specifically we focus on layer tuning for feed45;forward network in the Transformer namely FL45;tuning. It introduces additional units into the hidden layer of each feed45;forward network. We conduct extensive experiments on the public CLUE benchmark. The results show that 1) Our FL45;tuning outperforms prompt tuning methods under both full45;data and few45;shot settings in almost all cases. In particular it improves accuracy by 17.9337; (full45;data setting) on WSC 1.0 and F1 by 16.14237; (few45;shot setting) on CLUENER over P45;tuning v2. 2) Our FL45;tuning is more stable and converges about 1.17 times faster than P45;tuning v2. 3) With only about 337; of Transformers parameters to be trained FL45;tuning is comparable with fine45;tuning on most datasets and significantly outperforms fine45;tuning (e.g. accuracy improved by 12.937; on WSC 1.1) on several datasets. The source codes are available at https://github.com/genggui001/FL&#45;Tuning.
