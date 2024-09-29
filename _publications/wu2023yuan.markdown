---
layout: publication
title: YUAN 2.0\: A Large Language Model With Localized Filtering-based Attention
authors: Wu Shaohua, Zhao Xudong, Wang Shenling, Luo Jiangang, Li Lingjun, Chen Xi, Zhao Bing, Wang Wei, Yu Tong, Zhang Rongguo, Zhang Jiahua, Wang Chao
conference: "Arxiv"
year: 2023
bibkey: wu2023yuan
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.15786"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
In this work we develop and release Yuan 2.0 a series of large language models with parameters ranging from 2.1 billion to 102.6 billion. The Localized Filtering-based Attention (LFA) is introduced to incorporate prior knowledge of local dependencies of natural language into Attention. A data filtering and generating system is presented to build pre-training and fine-tuning dataset in high quality. A distributed training method with non-uniform pipeline parallel data parallel and optimizer parallel is proposed which greatly reduces the bandwidth requirements of intra-node communication and achieves good performance in large-scale distributed training. Yuan 2.0 models display impressive ability in code generation math problem-solving and chatting compared with existing models. The latest version of YUAN 2.0 including model weights and source code is accessible at Github.
