---
layout: publication
title: 'Datasculpt: Crafting Data Landscapes For Long-context Llms Through Multi-objective Partitioning'
authors: Keer Lu, Xiaonan Nie, Zheng Liang, Da Pan, Shusen Zhang, Keshi Zhao, Weipeng Chen, Zenan Zhou, Guosheng Dong, Bin Cui, Wentao Zhang
conference: "Arxiv"
year: 2024
bibkey: lu2024crafting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.00997'}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Applications', 'Tools']
---
In recent years, Large Language Models (LLMs) have demonstrated significant
improvements across a variety of tasks, one of which is the long-context
capability. The key to improving long-context performance lies in effective
data organization and management strategies that integrate data from multiple
domains and optimize the context window during training. Through extensive
experimental analysis, we identified three key challenges in designing
effective data management strategies that enable the model to achieve
long-context capability without sacrificing performance in other tasks: (1) a
shortage of long documents across multiple domains, (2) effective construction
of context windows, and (3) efficient organization of large-scale datasets. To
address these challenges, we introduce DataSculpt, a novel data management
framework designed for long-context training. We first formulate the
organization of training data as a multi-objective combinatorial optimization
problem, focusing on attributes including relevance, homogeneity, integrity,
and efficiency. Specifically, our approach utilizes a coarse-to-fine
methodology to optimize training data organization both efficiently and
effectively. We begin by clustering the data based on semantic similarity
(coarse), followed by a multi-objective greedy search within each cluster to
score and concatenate documents into various context windows (fine). Our
comprehensive evaluations demonstrate that DataSculpt significantly enhances
long-context training performance, resulting in improvements of 18.09% in
retrieval augmentation, 21.23% in summarization, 21.27% in reading
comprehension, and a 3.81% increase in code completion, while also maintaining
overall model proficiency with a 4.88% improvement.
