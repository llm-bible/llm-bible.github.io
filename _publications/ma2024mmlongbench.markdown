---
layout: publication
title: Mmlongbench45;doc Benchmarking Long45;context Document Understanding With Visualizations
authors: Ma Yubo, Zang Yuhang, Chen Liangyu, Chen Meiqi, Jiao Yizhu, Li Xinze, Lu Xinyuan, Liu Ziyu, Ma Yan, Dong Xiaoyi, Zhang Pan, Pan Liangming, Jiang Yu-gang, Wang Jiaqi, Cao Yixin, Sun Aixin
conference: "Arxiv"
year: 2024
bibkey: ma2024mmlongbench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01523"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning']
---
Understanding documents with rich layouts and multi45;modal components is a long45;standing and practical task. Recent Large Vision45;Language Models (LVLMs) have made remarkable strides in various tasks particularly in single45;page document understanding (DU). However their abilities on long45;context DU remain an open problem. This work presents MMLongBench45;Doc a long45;context multi45;modal benchmark comprising 1062 expert45;annotated questions. Distinct from previous datasets it is constructed upon 130 lengthy PDF45;formatted documents with an average of 49.4 pages and 20971 textual tokens. Towards comprehensive evaluation answers to these questions rely on pieces of evidence from (1) different sources (text image chart table and layout structure) and (2) various locations (i.e. page number). Moreover 33.237; of the questions are cross45;page questions requiring evidence across multiple pages. 22.837; of the questions are designed to be unanswerable for detecting potential hallucinations. Experiments on 14 LVLMs demonstrate that long45;context DU greatly challenges current models. Notably the best45;performing model GPT45;4o achieves an F1 score of only 42.737; while the second45;best GPT45;4V scores 31.437;. Furthermore 12 LVLMs (all except GPT45;4o and GPT45;4V) even present worse performance than their LLM counterparts which are fed with lossy45;parsed OCR documents. These results validate the necessity of future research toward more capable long45;context LVLMs. Project Page https://mayubo2333.github.io/MMLongBench&#45;Doc
