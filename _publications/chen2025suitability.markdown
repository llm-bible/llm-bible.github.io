---
layout: publication
title: 'On The Suitability Of Reinforcement Fine-tuning To Visual Tasks'
authors: Xiaxu Chen, Wei Li, Chunxu Liu, Chi Xie, Xiaoyan Hu, Chengqian Ma, Feng Zhu, Rui Zhao
conference: "Arxiv"
year: 2025
bibkey: chen2025suitability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.05682"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Reinforcement Fine-Tuning (RFT) is proved to be greatly valuable for
enhancing the reasoning ability of LLMs. Researchers have been starting to
apply RFT to MLLMs, hoping it will also enhance the capabilities of visual
understanding. However, these works are at a very early stage and have not
examined how suitable RFT actually is for visual tasks. In this work, we
endeavor to understand the suitabilities and limitations of RFT for visual
tasks, through experimental analysis and observations. We start by quantitative
comparisons on various tasks, which shows RFT is generally better than SFT on
visual tasks. %especially when the number of training samples are limited. To
check whether such advantages are brought up by the reasoning process, we
design a new reward that encourages the model to ``think'' more, whose results
show more thinking can be beneficial for complicated tasks but harmful for
simple tasks. We hope this study can provide more insight for the rapid
advancements on this topic.
