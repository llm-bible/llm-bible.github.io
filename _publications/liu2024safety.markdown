---
layout: publication
title: SAFETY45;J Evaluating Safety With Critique
authors: Liu Yixiu, Zheng Yuxiang, Xia Shijie, Li Jiajun, Tu Yi, Song Chaoling, Liu Pengfei
conference: "Arxiv"
year: 2024
bibkey: liu2024safety
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17075"}
  - {name: "Code", url: "https://github.com/GAIR&#45;NLP/Safety&#45;J"}
tags: ['Ethics And Bias', 'Has Code', 'Interpretability And Explainability', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
The deployment of Large Language Models (LLMs) in content generation raises significant safety concerns particularly regarding the transparency and interpretability of content evaluations. Current methods primarily focused on binary safety classifications lack mechanisms for detailed critique limiting their utility for model improvement and user trust. To address these limitations we introduce SAFETY45;J a bilingual generative safety evaluator for English and Chinese with critique45;based judgment. SAFETY45;J utilizes a robust training dataset that includes diverse dialogues and augmented query45;response pairs to assess safety across various scenarios comprehensively. We establish an automated meta45;evaluation benchmark that objectively assesses the quality of critiques with minimal human intervention facilitating scalable and continuous improvement. Additionally SAFETY45;J employs an iterative preference learning technique to dynamically refine safety assessments based on meta45;evaluations and critiques. Our evaluations demonstrate that SAFETY45;J provides more nuanced and accurate safety evaluations thereby enhancing both critique quality and predictive reliability in complex content scenarios. To facilitate further research and application we open45;source SAFETY45;Js training protocols datasets and code at https://github.com/GAIR&#45;NLP/Safety&#45;J.
