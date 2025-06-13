---
layout: publication
title: 'Mergeit: From Selection To Merging For Efficient Instruction Tuning'
authors: Hongyi Cai, Yuqian Fu, Hongming Fu, Bo Zhao
conference: "Arxiv"
year: 2025
bibkey: cai2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00034'}
  - {name: "Code", url: 'https://github.com/XcloudFance/MergeIT'}
tags: ['Has Code', 'Training Techniques', 'Merging']
---
Instruction tuning is crucial for optimizing Large Language Models (LLMs),
yet mainstream data selection methods heavily rely on LLMs as instruction
quality scorers, leading to high computational costs and reduced data
diversity. To address these limitations, we propose MergeIT, a novel LLM-based
Merging strategy for better Instruction Tuning that shifts the focus from
selection to synthesis. MergeIT operates in two stages: first, topic-aware
filtering clusters and refines the dataset, preserving diversity while
eliminating redundancy without relying on LLM-based scoring. Second, LLM-based
merging synthesizes semantically similar instructions into more informative and
compact training data, enhancing data richness while further reducing dataset
size. Experimental results demonstrate that MergeIT enables efficient, diverse,
and scalable instruction selection and synthesis, establishing LLM-based
merging as a promising alternative to conventional scoring-based selection
methods for instruction tuning. Our source code and datasets are now available
at https://github.com/XcloudFance/MergeIT
