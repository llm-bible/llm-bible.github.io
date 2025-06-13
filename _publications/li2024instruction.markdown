---
layout: publication
title: 'Instruction-guided Fusion Of Multi-layer Visual Features In Large Vision-language Models'
authors: Xu Li, Yi Zheng, Haotian Chen, Xiaolei Chen, Yuxuan Liang, Chenghang Lai, Bin Li, Xiangyang Xue
conference: "Arxiv"
year: 2024
bibkey: li2024instruction
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.08443'}
tags: ['Reinforcement Learning', 'Multimodal Models', 'Merging']
---
Large Vision-Language Models (LVLMs) have achieved remarkable success in a
wide range of multimodal tasks by integrating pre-trained vision encoders and
large language models. However, current LVLMs primarily rely on visual features
extracted from the final layers of the vision encoder, overlooking the
complementary information available in shallower layers. While recent
approaches have explored the use of multilayer visual features in LVLMs, they
tend to be task-agnostic and fail to examine the dependencies of hierarchical
visual features on specific tasks. To address these gaps, we systematically
investigate the contributions of visual features from different encoder layers
using 18 benchmarks spanning 6 task categories. Our findings reveal that
multilayer features provide complementary strengths with varying task
dependencies, and uniform fusion leads to suboptimal performance. Building on
these insights, we propose the instruction-guided vision aggregator, a module
that dynamically integrates multi-layer visual features based on textual
instructions, without increasing the number of visual tokens. Extensive
evaluations demonstrate the superior performance of our method. Additionally,
an in-depth analysis of the aggregator's behavior highlights the dominance of
mid-to-high-level features in semantic-rich tasks and the critical role of
low-level features in fine-grained perception.
