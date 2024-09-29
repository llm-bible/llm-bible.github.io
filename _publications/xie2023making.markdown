---
layout: publication
title: Making Small Language Models Better Multi45;task Learners With Mixture45;of45;task45;adapters
authors: Xie Yukang, Wang Chengyu, Yan Junbing, Zhou Jiyong, Deng Feiqi, Huang Jun
conference: "Arxiv"
year: 2023
bibkey: xie2023making
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.11042"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Recently Large Language Models (LLMs) have achieved amazing zero45;shot learning performance over a variety of Natural Language Processing (NLP) tasks especially for text generative tasks. Yet the large size of LLMs often leads to the high computational cost of model training and online deployment. In our work we present ALTER a system that effectively builds the multi45;tAsk Learners with mixTure45;of45;task45;adaptERs upon small language models (with <1B parameters) to address multiple NLP tasks simultaneously capturing the commonalities and differences between tasks in order to support domain45;specific applications. Specifically in ALTER we propose the Mixture45;of45;Task45;Adapters (MTA) module as an extension to the transformer architecture for the underlying model to capture the intra45;task and inter45;task knowledge. A two45;stage training method is further proposed to optimize the collaboration between adapters at a small computational cost. Experimental results over a mixture of NLP tasks show that our proposed MTA architecture and the two45;stage training method achieve good performance. Based on ALTER we have also produced MTA45;equipped language models for various domains.
