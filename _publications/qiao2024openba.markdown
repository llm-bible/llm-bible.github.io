---
layout: publication
title: 'Openba-v2: Reaching 77.3% High Compression Ratio With Fast Multi-stage Pruning'
authors: Dan Qiao, Yi Su, Pinzheng Wang, Jing Ye, Wenjing Xie, Yuechi Zhou, Yuyang Ding, Zecheng Tang, Jikai Wang, Yixin Ji, Yue Wang, Pei Guo, Zechen Sun, Zikang Zhang, Juntao Li, Pingfu Chao, Wenliang Chen, Guohong Fu, Guodong Zhou, Qiaoming Zhu, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: qiao2024openba
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.05957'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Applications', 'Pruning', 'Pre-Training']
---
Large Language Models (LLMs) have played an important role in many fields due
to their powerful capabilities.However, their massive number of parameters
leads to high deployment requirements and incurs significant inference costs,
which impedes their practical applications. Training smaller models is an
effective way to address this problem. Therefore, we introduce OpenBA-V2, a
3.4B model derived from multi-stage compression and continual pre-training from
the original 15B OpenBA model. OpenBA-V2 utilizes more data, more flexible
training objectives, and techniques such as layer pruning, neural pruning, and
vocabulary pruning to achieve a compression rate of 77.3% with minimal
performance loss. OpenBA-V2 demonstrates competitive performance compared to
other open-source models of similar size, achieving results close to or on par
with the 15B OpenBA model in downstream tasks such as common sense reasoning
and Named Entity Recognition (NER). OpenBA-V2 illustrates that LLMs can be
compressed into smaller ones with minimal performance loss by employing
advanced training objectives and data strategies, which may help deploy LLMs in
resource-limited scenarios.
