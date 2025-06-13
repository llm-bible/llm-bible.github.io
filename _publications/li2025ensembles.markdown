---
layout: publication
title: 'Ensembles Of Low-rank Expert Adapters'
authors: Yinghao Li, Vianne Gao, Chao Zhang, Mohamadali Torkamani
conference: "Arxiv"
year: 2025
bibkey: li2025ensembles
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00089'}
tags: ['Efficiency and Optimization', 'Tools', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Pretraining Methods']
---
The training and fine-tuning of large language models (LLMs) often involve
diverse textual data from multiple sources, which poses challenges due to
conflicting gradient directions, hindering optimization and specialization.
These challenges can undermine model generalization across tasks, resulting in
reduced downstream performance. Recent research suggests that fine-tuning LLMs
on carefully selected, task-specific subsets of data can match or even surpass
the performance of using the entire dataset. Building on these insights, we
propose the Ensembles of Low-Rank Expert Adapters (ELREA) framework to improve
the model's capability to handle diverse tasks. ELREA clusters the training
instructions based on their gradient directions, representing different areas
of expertise and thereby reducing conflicts during optimization. Expert
adapters are then trained on these clusters, utilizing the low-rank adaptation
(LoRA) technique to ensure training efficiency and model scalability. During
inference, ELREA combines predictions from the most relevant expert adapters
based on the input data's gradient similarity to the training clusters,
ensuring optimal adapter selection for each task. Experiments show that our
method outperforms baseline LoRA adapters trained on the full dataset and other
ensemble approaches with similar training and inference complexity across a
range of domain-specific tasks.
