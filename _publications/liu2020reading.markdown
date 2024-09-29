---
layout: publication
title: Rikinet Reading Wikipedia Pages For Natural Question Answering
authors: Liu Dayiheng, Gong Yeyun, Fu Jie, Yan Yu, Chen Jiusheng, Jiang Daxin, Lv Jiancheng, Duan Nan
conference: "Arxiv"
year: 2020
bibkey: liu2020reading
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.14560"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Transformer']
---
Reading long documents to answer open45;domain questions remains challenging in natural language understanding. In this paper we introduce a new model called RikiNet which reads Wikipedia pages for natural question answering. RikiNet contains a dynamic paragraph dual45;attention reader and a multi45;level cascaded answer predictor. The reader dynamically represents the document and question by utilizing a set of complementary attention mechanisms. The representations are then fed into the predictor to obtain the span of the short answer the paragraph of the long answer and the answer type in a cascaded manner. On the Natural Questions (NQ) dataset a single RikiNet achieves 74.3 F1 and 57.9 F1 on long45;answer and short45;answer tasks. To our best knowledge it is the first single model that outperforms the single human performance. Furthermore an ensemble RikiNet obtains 76.1 F1 and 61.3 F1 on long45;answer and short45;answer tasks achieving the best performance on the official NQ leaderboard
