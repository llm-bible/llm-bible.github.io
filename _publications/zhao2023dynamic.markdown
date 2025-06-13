---
layout: publication
title: 'Dynamic Demonstrations Controller For In-context Learning'
authors: Fei Zhao, Taotian Pang, Zhen Wu, Zheng Ma, Shujian Huang, Xinyu Dai
conference: "Arxiv"
year: 2023
bibkey: zhao2023dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00385"}
tags: ['Prompting', 'In-Context Learning']
---
In-context learning (ICL) is a new paradigm for natural language processing
(NLP), where a large language model (LLM) observes a small number of
demonstrations and a test instance as its input, and directly makes predictions
without updating model parameters. Previous studies have revealed that ICL is
sensitive to the selection and the ordering of demonstrations. However, there
are few studies regarding the impact of the demonstration number on the ICL
performance within a limited input length of LLM, because it is commonly
believed that the number of demonstrations is positively correlated with model
performance. In this paper, we found this conclusion does not always hold true.
Through pilot experiments, we discover that increasing the number of
demonstrations does not necessarily lead to improved performance. Building upon
this insight, we propose a Dynamic Demonstrations Controller (D\\(^2\\)Controller),
which can improve the ICL performance by adjusting the number of demonstrations
dynamically. The experimental results show that D\\(^2\\)Controller yields a 4.6%
relative improvement on ten different sizes of LLMs across ten datasets.
Moreover, we also extend our method to previous ICL models and achieve
competitive results.
