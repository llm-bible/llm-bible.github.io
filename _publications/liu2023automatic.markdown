---
layout: publication
title: 'Coachlm: Automatic Instruction Revisions Improve The Data Quality In LLM Instruction Tuning'
authors: Yilun Liu, Shimin Tao, Xiaofeng Zhao, Ming Zhu, Wenbing Ma, Junhao Zhu, Chang Su, Yutai Hou, Miao Zhang, Min Zhang, Hongxia Ma, Li Zhang, Hao Yang, Yanfei Jiang
conference: "Arxiv"
year: 2023
bibkey: liu2023automatic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.13246'}
  - {name: "Code", url: 'https://github.com/lunyiliu/CoachLM)'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Instruction tuning is crucial for enabling Language Learning Models (LLMs) in
responding to human instructions. The quality of instruction pairs used for
tuning greatly affects the performance of LLMs. However, the manual creation of
high-quality instruction datasets is costly, leading to the adoption of
automatic generation of instruction pairs by LLMs as a popular alternative. To
ensure the high quality of LLM-generated instruction datasets, several
approaches have been proposed. Nevertheless, existing methods either compromise
dataset integrity by filtering a large proportion of samples, or are unsuitable
for industrial applications. In this paper, instead of discarding low-quality
samples, we propose CoachLM, a novel approach to enhance the quality of
instruction datasets through automatic revisions on samples in the dataset.
CoachLM is trained from the samples revised by human experts and significantly
increases the proportion of high-quality samples in the dataset from 17.7% to
78.9%. The effectiveness of CoachLM is further assessed on various real-world
instruction test sets. The results show that CoachLM improves the
instruction-following capabilities of the instruction-tuned LLM by an average
of 29.9%, which even surpasses larger LLMs with nearly twice the number of
parameters. Furthermore, CoachLM is successfully deployed in a data management
system for LLMs at Huawei, resulting in an efficiency improvement of up to 20%
in the cleaning of 40k real-world instruction pairs. We release various assets
of CoachLM, including the training data, code and test set
(https://github.com/lunyiliu/CoachLM).
