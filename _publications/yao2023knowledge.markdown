---
layout: publication
title: Knowledge Plugins: Enhancing Large Language Models For Domain-specific Recommendations
authors: Yao Jing, Xu Wei, Lian Jianxun, Wang Xiting, Yi Xiaoyuan, Xie Xing
conference: "Arxiv"
year: 2023
bibkey: yao2023knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10779"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The significant progress of large language models (LLMs) provides a promising opportunity to build human-like systems for various practical applications. However when applied to specific task domains an LLM pre-trained on a general-purpose corpus may exhibit a deficit or inadequacy in two types of domain-specific knowledge. One is a comprehensive set of domain data that is typically large-scale and continuously evolving. The other is specific working patterns of this domain reflected in the data. The absence or inadequacy of such knowledge impacts the performance of the LLM. In this paper we propose a general paradigm that augments LLMs with DOmain-specific KnowledgE to enhance their performance on practical applications namely DOKE. This paradigm relies on a domain knowledge extractor working in three steps 1) preparing effective knowledge for the task; 2) selecting the knowledge for each specific sample; and 3) expressing the knowledge in an LLM-understandable way. Then the extracted knowledge is incorporated through prompts without any computational cost of model fine-tuning. We instantiate the general paradigm on a widespread application i.e. recommender systems where critical item attributes and collaborative filtering signals are incorporated. Experimental results demonstrate that DOKE can substantially improve the performance of LLMs in specific domains.
