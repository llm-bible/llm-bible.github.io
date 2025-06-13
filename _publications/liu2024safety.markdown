---
layout: publication
title: 'SAFETY-J: Evaluating Safety With Critique'
authors: Yixiu Liu, Yuxiang Zheng, Shijie Xia, Jiajun Li, Yi Tu, Chaoling Song, Pengfei Liu
conference: "Arxiv"
year: 2024
bibkey: liu2024safety
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.17075'}
  - {name: "Code", url: 'https://github.com/GAIR-NLP/Safety-J'}
tags: ['Has Code', 'Interpretability and Explainability', 'Training Techniques', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Responsible AI']
---
The deployment of Large Language Models (LLMs) in content generation raises
significant safety concerns, particularly regarding the transparency and
interpretability of content evaluations. Current methods, primarily focused on
binary safety classifications, lack mechanisms for detailed critique, limiting
their utility for model improvement and user trust. To address these
limitations, we introduce SAFETY-J, a bilingual generative safety evaluator for
English and Chinese with critique-based judgment. SAFETY-J utilizes a robust
training dataset that includes diverse dialogues and augmented query-response
pairs to assess safety across various scenarios comprehensively. We establish
an automated meta-evaluation benchmark that objectively assesses the quality of
critiques with minimal human intervention, facilitating scalable and continuous
improvement. Additionally, SAFETY-J employs an iterative preference learning
technique to dynamically refine safety assessments based on meta-evaluations
and critiques. Our evaluations demonstrate that SAFETY-J provides more nuanced
and accurate safety evaluations, thereby enhancing both critique quality and
predictive reliability in complex content scenarios. To facilitate further
research and application, we open-source SAFETY-J's training protocols,
datasets, and code at https://github.com/GAIR-NLP/Safety-J.
