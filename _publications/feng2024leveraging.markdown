---
layout: publication
title: Legend Leveraging Representation Engineering To Annotate Safety Margin For Preference Datasets
authors: Feng Duanyu, Qin Bowen, Huang Chen, Huang Youcheng, Zhang Zheng, Lei Wenqiang
conference: "Arxiv"
year: 2024
bibkey: feng2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08124"}
tags: ['Applications', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Tools', 'Training Techniques']
---
The success of the reward model in distinguishing between responses with subtle safety differences depends critically on the high-quality preference dataset which should capture the fine-grained nuances of harmful and harmless responses. This motivates the need to develop a dataset involving preference margins which accurately quantify how harmless one response is compared to another. In this paper we take the first step to propose an effective and cost-efficient framework to promote the margin-enhanced preference dataset development. Our framework Legend Leverages representation engineering to annotate preference datasets. It constructs the specific direction within the LLMs embedding space that represents safety. By leveraging this safety direction Legend can then leverage the semantic distances of paired responses along this direction to annotate margins automatically. We experimentally demonstrate our effectiveness in both reward modeling and harmless alignment for LLMs. Legend also stands out for its efficiency requiring only the inference time rather than additional training. This efficiency allows for easier implementation and scalability making Legend particularly valuable for practical applications in aligning LLMs with safe conversations.
