---
layout: publication
title: 'Model-glue: Democratized LLM Scaling For A Large Model Zoo In The Wild'
authors: Xinyu Zhao, Guoheng Sun, Ruisi Cai, Yukun Zhou, Pingzhi Li, Peihao Wang, Bowen Tan, Yexiao He, Li Chen, Yi Liang, Beidi Chen, Binhang Yuan, Hongyi Wang, Ang Li, Zhangyang Wang, Tianlong Chen
conference: "Arxiv"
year: 2024
bibkey: zhao2024model
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.05357'}
  - {name: "Code", url: 'https://github.com/Model-GLUE/Model-GLUE'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Training Techniques', 'Model Architecture', 'Merging']
---
As Large Language Models (LLMs) excel across tasks and specialized domains,
scaling LLMs based on existing models has garnered significant attention, which
faces the challenge of decreasing performance when combining disparate models.
Various techniques have been proposed for the aggregation of pre-trained LLMs,
including model merging, Mixture-of-Experts, and stacking. Despite their
merits, a comprehensive comparison and synergistic application of them to a
diverse model zoo is yet to be adequately addressed. In light of this research
gap, this paper introduces Model-GLUE, a holistic LLM scaling guideline. First,
our work starts with a benchmarking of existing LLM scaling techniques,
especially selective merging, and variants of mixture. Utilizing the insights
from the benchmark results, we formulate an optimal strategy for the selection
and aggregation of a heterogeneous model zoo characterizing different
architectures and initialization.Our methodology involves the clustering of
mergeable models and optimal merging strategy selection, and the integration of
clusters through a model mixture. Finally, evidenced by our experiments on a
diverse Llama-2-based model zoo, Model-GLUE shows an average performance
enhancement of 5.61%, achieved without additional training. Codes are available
at: https://github.com/Model-GLUE/Model-GLUE.
