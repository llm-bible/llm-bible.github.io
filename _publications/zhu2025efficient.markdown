---
layout: publication
title: 'EAVIT: Efficient And Accurate Human Value Identification From Text Data Via Llms'
authors: Wenhao Zhu, Yuhang Xie, Guojie Song, Xin Zhang
conference: "Arxiv"
year: 2025
bibkey: zhu2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12792'}
tags: ['Interpretability and Explainability', 'Training Techniques', 'BERT', 'Model Architecture', 'Tools', 'GPT', 'Merging', 'Prompting']
---
The rapid evolution of large language models (LLMs) has revolutionized various fields, including the identification and discovery of human values within text data. While traditional NLP models, such as BERT, have been employed for this task, their ability to represent textual data is significantly outperformed by emerging LLMs like GPTs. However, the performance of online LLMs often degrades when handling long contexts required for value identification, which also incurs substantial computational costs. To address these challenges, we propose EAVIT, an efficient and accurate framework for human value identification that combines the strengths of both locally fine-tunable and online black-box LLMs. Our framework employs a value detector - a small, local language model - to generate initial value estimations. These estimations are then used to construct concise input prompts for online LLMs, enabling accurate final value identification. To train the value detector, we introduce explanation-based training and data generation techniques specifically tailored for value identification, alongside sampling strategies to optimize the brevity of LLM input prompts. Our approach effectively reduces the number of input tokens by up to 1/6 compared to directly querying online LLMs, while consistently outperforming traditional NLP methods and other LLM-based strategies.
