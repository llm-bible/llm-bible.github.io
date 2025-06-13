---
layout: publication
title: 'Insbank: Evolving Instruction Subset For Ongoing Alignment'
authors: Jiayi Shi, Yiwei Li, Shaoxiong Feng, Peiwen Yuan, Xinglin Wang, Yueqi Zhang, Chuyi Tan, Boyuan Pan, Huan Ren, Yao Hu, Kan Li
conference: "Arxiv"
year: 2025
bibkey: shi2025evolving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11419"}
tags: ['Training Techniques', 'RAG', 'Tools', 'Efficiency and Optimization']
---
Large language models (LLMs) typically undergo instruction tuning to enhance
alignment. Recent studies emphasize that quality and diversity of instruction
data are more crucial than quantity, highlighting the need to select diverse,
high-quality subsets to reduce training costs. However, how to evolve these
selected subsets alongside the development of new instruction data remains
insufficiently explored. To achieve LLMs' ongoing alignment, we introduce
Instruction Bank (InsBank), a continuously updated repository that integrates
the latest valuable instruction data. We further propose Progressive
Instruction Bank Evolution (PIBE), a novel framework designed to evolve InsBank
effectively and efficiently over time. PIBE employs a gradual data selection
strategy to maintain long-term efficiency, leveraging a representation-based
diversity score to capture relationships between data points and retain
historical information for comprehensive diversity evaluation. This also allows
for flexible combination of diversity and quality scores during data selection
and ranking. Extensive experiments demonstrate that PIBE significantly
outperforms baselines in InsBank evolution and is able to extract
budget-specific subsets, demonstrating its effectiveness and adaptability.
