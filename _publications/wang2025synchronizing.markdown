---
layout: publication
title: 'CODESYNC: Synchronizing Large Language Models With Dynamic Code Evolution At Scale'
authors: Chenlong Wang, Zhaoyang Chu, Zhengxiang Cheng, Xuyi Yang, Kaiyue Qiu, Yao Wan, Zhou Zhao, Xuanhua Shi, Dongping Chen
conference: "Arxiv"
year: 2025
bibkey: wang2025synchronizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16645"}
  - {name: "Code", url: "https://github.com/Lucky-voyage/Code-Sync"}
tags: ['Responsible AI', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Large Language Models (LLMs) have exhibited exceptional performance in
software engineering yet face challenges in adapting to continually evolving
code knowledge, particularly regarding the frequent updates of third-party
library APIs. This limitation, stemming from static pre-training datasets,
often results in non-executable code or implementations with suboptimal safety
and efficiency. To this end, this paper introduces CODESYNC, a data engine for
identifying outdated code patterns and collecting real-time code knowledge
updates from Python third-party libraries. Building upon CODESYNC, we develop
CODESYNCBENCH, a comprehensive benchmark for assessing LLMs' ability to stay
synchronized with code evolution, which covers real-world updates for 220 APIs
from six Python libraries. Our benchmark offers 3,300 test cases across three
evaluation tasks and an update-aware instruction tuning dataset consisting of
2,200 training samples. Extensive experiments on 14 state-of-the-art LLMs
reveal that they struggle with dynamic code evolution, even with the support of
advanced knowledge updating methods (e.g., DPO, ORPO, and SimPO). We believe
that our benchmark can offer a strong foundation for the development of more
effective methods for real-time code knowledge updating in the future. The
experimental code and dataset are publicly available at:
https://github.com/Lucky-voyage/Code-Sync.
