---
layout: publication
title: 'Exact And Efficient Unlearning For Large Language Model-based Recommendation'
authors: Zhiyu Hu, Yang Zhang, Minghao Xiao, Wenjie Wang, Fuli Feng, Xiangnan He
conference: "Arxiv"
year: 2024
bibkey: hu2024exact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10327"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
The evolving paradigm of Large Language Model-based Recommendation (LLMRec)
customizes Large Language Models (LLMs) through parameter-efficient fine-tuning
(PEFT) using recommendation data. The inclusion of user data in LLMs raises
privacy concerns. To protect users, the unlearning process in LLMRec,
specifically removing unusable data (e.g., historical behaviors) from
established LLMRec models, becomes crucial. However, existing unlearning
methods are insufficient for the unique characteristics of LLM-Rec, mainly due
to high computational costs or incomplete data erasure. In this study, we
introduce the Adapter Partition and Aggregation (APA) framework for exact and
efficient unlearning while maintaining recommendation performance. APA achieves
this by establishing distinct adapters for partitioned training data shards and
retraining only the adapters impacted by unusable data for unlearning. To
preserve recommendation performance and mitigate considerable inference costs,
APA employs parameter-level adapter aggregation with sample-adaptive attention
for individual testing samples. Extensive experiments substantiate the
effectiveness and efficiency of our proposed framework
