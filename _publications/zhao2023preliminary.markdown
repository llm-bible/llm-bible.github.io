---
layout: publication
title: 'A Preliminary Study Of The Intrinsic Relationship Between Complexity And Alignment'
authors: Yingxiu Zhao, Bowen Yu, Binyuan Hui, Haiyang Yu, Fei Huang, Yongbin Li, Nevin L. Zhang
conference: "Arxiv"
year: 2023
bibkey: zhao2023preliminary
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.05696'}
tags: ['Training Techniques']
---
Training large language models (LLMs) with open-domain instruction data has
yielded remarkable success in aligning to end tasks and human preferences.
Extensive research has highlighted the importance of the quality and diversity
of instruction data. However, the impact of data complexity, as a crucial
metric, remains relatively unexplored from three aspects: (1)where the
sustainability of performance improvements with increasing complexity is
uncertain; (2)whether the improvement brought by complexity merely comes from
introducing more training tokens; and (3)where the potential benefits of
incorporating instructions from easy to difficult are not yet fully understood.
In this paper, we propose Tree-Instruct to systematically enhance the
instruction complexity in a controllable manner. By adding a specified number
of nodes to instructions' semantic trees, this approach not only yields new
instruction data from the modified tree but also allows us to control the
difficulty level of modified instructions. Our preliminary experiments reveal
the following insights: (1)Increasing complexity consistently leads to
sustained performance improvements of LLMs. (2)Under the same token budget, a
few complex instructions outperform diverse yet simple instructions.
(3)Curriculum instruction tuning might not yield the anticipated results;
focusing on increasing complexity appears to be the key.
