---
layout: publication
title: Chimera&#58; A Lossless Decoding Method For Accelerating Large Language Models Inference By Fusing All Tokens
authors: Zeng Ziqian, Yu Jiahong, Pang Qianshi, Wang Zihao, Zhuang Huiping, Shao Hongen, Zou Xiaofeng
conference: "Arxiv"
year: 2024
bibkey: zeng2024lossless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15758"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'RAG', 'Tools']
---
Large language models (LLMs) have demonstrated remarkable capabilities across various tasks. However their widespread application is hindered by the resource-intensive decoding process. To address this challenge current approaches have incorporated additional decoding heads to enable parallel prediction of multiple subsequent tokens thereby achieving inference acceleration. Nevertheless the accuracy of these decoding heads falls short of the auto-regressive decoding approach. In light of these limitations we propose Chimera a novel framework specifically designed for speculative sampling. Within this framework we introduce a lightweight draft model that effectively utilizes previously generated tokens to predict subsequent words. To ensure both accuracy and efficiency we present two strategies within the lightweight draft model. Firstly we focus on capturing short-range dependencies at the bottom layer. Secondly we leverage the readily available representations from the original LLM.Through empirical evaluation on the Vicuna and LlaMA-2 series Chimera demonstrates impressive results achieving an average latency speedup ratio of 2.7x compared to the vanilla auto-regressive decoding approach. This highlights the potential of our proposed framework in significantly improving the efficiency of large language models during the decoding process.
