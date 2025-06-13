---
layout: publication
title: 'Ultra-fineweb: Efficient Data Filtering And Verification For High-quality LLM Training Data'
authors: Yudong Wang, Zixuan Fu, Jie Cai, Peijun Tang, Hongya Lyu, Yewei Fang, Zhi Zheng, Jie Zhou, Guoyang Zeng, Chaojun Xiao, Xu Han, Zhiyuan Liu
conference: "Arxiv"
year: 2025
bibkey: wang2025ultra
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05427"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'Security', 'Training Techniques']
---
Data quality has become a key factor in enhancing model performance with the
rapid development of large language models (LLMs). Model-driven data filtering
has increasingly become a primary approach for acquiring high-quality data.
However, it still faces two main challenges: (1) the lack of an efficient data
verification strategy makes it difficult to provide timely feedback on data
quality; and (2) the selection of seed data for training classifiers lacks
clear criteria and relies heavily on human expertise, introducing a degree of
subjectivity. To address the first challenge, we introduce an efficient
verification strategy that enables rapid evaluation of the impact of data on
LLM training with minimal computational cost. To tackle the second challenge,
we build upon the assumption that high-quality seed data is beneficial for LLM
training, and by integrating the proposed verification strategy, we optimize
the selection of positive and negative samples and propose an efficient data
filtering pipeline. This pipeline not only improves filtering efficiency,
classifier quality, and robustness, but also significantly reduces experimental
and inference costs. In addition, to efficiently filter high-quality data, we
employ a lightweight classifier based on fastText, and successfully apply the
filtering pipeline to two widely-used pre-training corpora, FineWeb and Chinese
FineWeb datasets, resulting in the creation of the higher-quality Ultra-FineWeb
dataset. Ultra-FineWeb contains approximately 1 trillion English tokens and 120
billion Chinese tokens. Empirical results demonstrate that the LLMs trained on
Ultra-FineWeb exhibit significant performance improvements across multiple
benchmark tasks, validating the effectiveness of our pipeline in enhancing both
data quality and training efficiency.
