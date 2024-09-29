---
layout: publication
title: Internlm45;law An Open Source Chinese Legal Large Language Model
authors: Fei Zhiwei, Zhang Songyang, Shen Xiaoyu, Zhu Dawei, Wang Xiao, Cao Maosong, Zhou Fengzhe, Li Yining, Zhang Wenwei, Lin Dahua, Chen Kai, Ge Jidong
conference: "Arxiv"
year: 2024
bibkey: fei2024internlm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14887"}
tags: ['Applications', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
While large language models (LLMs) have showcased impressive capabilities they struggle with addressing legal queries due to the intricate complexities and specialized expertise required in the legal field. In this paper we introduce InternLM45;Law a specialized LLM tailored for addressing diverse legal queries related to Chinese laws spanning from responding to standard legal questions (e.g. legal exercises in textbooks) to analyzing complex real45;world legal situations. We meticulously construct a dataset in the Chinese legal domain encompassing over 1 million queries and implement a data filtering and processing pipeline to ensure its diversity and quality. Our training approach involves a novel two45;stage process initially fine45;tuning LLMs on both legal45;specific and general45;purpose content to equip the models with broad knowledge followed by exclusive fine45;tuning on high45;quality legal data to enhance structured output generation. InternLM45;Law achieves the highest average performance on LawBench outperforming state45;of45;the45;art models including GPT45;4 on 13 out of 20 subtasks. We make InternLM45;Law and our dataset publicly available to facilitate future research in applying LLMs within the legal domain.
