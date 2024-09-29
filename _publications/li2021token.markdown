---
layout: publication
title: Terapipe Token45;level Pipeline Parallelism For Training Large45;scale Language Models
authors: Li Zhuohan, Zhuang Siyuan, Guo Shiyuan, Zhuo Danyang, Zhang Hao, Song Dawn, Stoica Ion
conference: "Arxiv"
year: 2021
bibkey: li2021token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.07988"}
  - {name: "Code", url: "https://github.com/zhuohan123/terapipe"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Model parallelism has become a necessity for training modern large45;scale deep language models. In this work we identify a new and orthogonal dimension from existing model parallel approaches it is possible to perform pipeline parallelism within a single training sequence for Transformer45;based language models thanks to its autoregressive property. This enables a more fine45;grained pipeline compared with previous work. With this key idea we design TeraPipe a high45;performance token45;level pipeline parallel algorithm for synchronous model45;parallel training of Transformer45;based language models. We develop a novel dynamic programming45;based algorithm to calculate the optimal pipelining execution scheme given a specific model and cluster configuration. We show that TeraPipe can speed up the training by 5.0x for the largest GPT45;3 model with 175 billion parameters on an AWS cluster with 48 p3.16xlarge instances compared with state45;of45;the45;art model45;parallel methods. The code for reproduction can be found at https://github.com/zhuohan123/terapipe
