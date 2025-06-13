---
layout: publication
title: 'Internlm-law: An Open Source Chinese Legal Large Language Model'
authors: Zhiwei Fei, Songyang Zhang, Xiaoyu Shen, Dawei Zhu, Xiao Wang, Maosong Cao, Fengzhe Zhou, Yining Li, Wenwei Zhang, Dahua Lin, Kai Chen, Jidong Ge
conference: "Arxiv"
year: 2024
bibkey: fei2024internlm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.14887'}
tags: ['RAG', 'Training Techniques', 'GPT', 'Model Architecture', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
While large language models (LLMs) have showcased impressive capabilities,
they struggle with addressing legal queries due to the intricate complexities
and specialized expertise required in the legal field. In this paper, we
introduce InternLM-Law, a specialized LLM tailored for addressing diverse legal
queries related to Chinese laws, spanning from responding to standard legal
questions (e.g., legal exercises in textbooks) to analyzing complex real-world
legal situations. We meticulously construct a dataset in the Chinese legal
domain, encompassing over 1 million queries, and implement a data filtering and
processing pipeline to ensure its diversity and quality. Our training approach
involves a novel two-stage process: initially fine-tuning LLMs on both
legal-specific and general-purpose content to equip the models with broad
knowledge, followed by exclusive fine-tuning on high-quality legal data to
enhance structured output generation. InternLM-Law achieves the highest average
performance on LawBench, outperforming state-of-the-art models, including
GPT-4, on 13 out of 20 subtasks. We make InternLM-Law and our dataset publicly
available to facilitate future research in applying LLMs within the legal
domain.
