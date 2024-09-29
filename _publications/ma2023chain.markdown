---
layout: publication
title: Chain45;of45;skills A Configurable Model For Open45;domain Question Answering
authors: Ma Kaixin, Cheng Hao, Zhang Yu, Liu Xiaodong, Nyberg Eric, Gao Jianfeng
conference: "Arxiv"
year: 2023
bibkey: ma2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.03130"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
The retrieval model is an indispensable component for real45;world knowledge45;intensive tasks e.g. open45;domain question answering (ODQA). As separate retrieval skills are annotated for different datasets recent work focuses on customized methods limiting the model transferability and scalability. In this work we propose a modular retriever where individual modules correspond to key skills that can be reused across datasets. Our approach supports flexible skill configurations based on the target domain to boost performance. To mitigate task interference we design a novel modularization parameterization inspired by sparse Transformer. We demonstrate that our model can benefit from self45;supervised pretraining on Wikipedia and fine45;tuning using multiple ODQA datasets both in a multi45;task fashion. Our approach outperforms recent self45;supervised retrievers in zero45;shot evaluations and achieves state45;of45;the45;art fine45;tuned retrieval performance on NQ HotpotQA and OTT45;QA.
