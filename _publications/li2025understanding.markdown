---
layout: publication
title: 'Understanding And Mitigating The Bias Inheritance In Llm-based Data Augmentation On Downstream Tasks'
authors: Miaomiao Li, Hao Chen, Yang Wang, Tingyuan Zhu, Weijia Zhang, Kaijie Zhu, Kam-fai Wong, Jindong Wang
conference: "Arxiv"
year: 2025
bibkey: li2025understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04419"}
tags: ['Security', 'Training Techniques', 'Fairness', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
Generating synthetic datasets via large language models (LLMs) themselves has
emerged as a promising approach to improve LLM performance. However, LLMs
inherently reflect biases present in their training data, leading to a critical
challenge: when these models generate synthetic data for training, they may
propagate and amplify their inherent biases that can significantly impact model
fairness and robustness on downstream tasks--a phenomenon we term bias
inheritance. This work presents the first systematic investigation in
understanding, analyzing, and mitigating bias inheritance. We study this
problem by fine-tuning LLMs with a combined dataset consisting of original and
LLM-augmented data, where bias ratio represents the proportion of augmented
data. Through systematic experiments across 10 classification and generation
tasks, we analyze how 6 different types of biases manifest at varying bias
ratios. Our results reveal that bias inheritance has nuanced effects on
downstream tasks, influencing both classification tasks and generation tasks
differently. Then, our analysis identifies three key misalignment factors:
misalignment of values, group data, and data distributions. Based on these
insights, we propose three mitigation strategies: token-based, mask-based, and
loss-based approaches. Experiments demonstrate that these strategies also work
differently on various tasks and bias, indicating the substantial challenges to
fully mitigate bias inheritance. We hope this work can provide valuable
insights to the research of LLM data augmentation.
