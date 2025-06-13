---
layout: publication
title: 'Towards Better Understanding Table Instruction Tuning: Decoupling The Effects From Data Versus Models'
authors: Naihao Deng, Sheng Zhang, Henghui Zhu, Shuaichen Chang, Jiani Zhang, Alexander Hanbo Li, Chung-wei Hang, Hideo Kobayashi, Yiqun Hu, Patrick Ng
conference: "Arxiv"
year: 2025
bibkey: deng2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14717"}
tags: ['RAG', 'Training Techniques']
---
Recent advances in natural language processing have leveraged instruction
tuning to enhance Large Language Models (LLMs) for table-related tasks.
However, previous works train different base models with different training
data, lacking an apples-to-apples comparison across the result table LLMs. To
address this, we fine-tune base models from the Mistral, OLMo, and Phi families
on existing public training datasets. Our replication achieves performance on
par with or surpassing existing table LLMs, establishing new state-of-the-art
performance on Hitab, a table question-answering dataset. More importantly,
through systematic out-of-domain evaluation, we decouple the contributions of
training data and the base model, providing insight into their individual
impacts. In addition, we assess the effects of table-specific instruction
tuning on general-purpose benchmarks, revealing trade-offs between
specialization and generalization.
