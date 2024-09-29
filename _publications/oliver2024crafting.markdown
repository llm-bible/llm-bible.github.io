---
layout: publication
title: Crafting Efficient Fine45;tuning Strategies For Large Language Models
authors: Oliver Michael, Wang Guan
conference: "Arxiv"
year: 2024
bibkey: oliver2024crafting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13906"}
tags: ['Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
This paper addresses the challenges of efficiently fine45;tuning large language models (LLMs) by exploring data efficiency and hyperparameter optimization. We investigate the minimum data required for effective fine45;tuning and propose a novel hyperparameter optimization method that leverages early45;stage model performance. Our experiments demonstrate that fine45;tuning with as few as 200 samples can improve model accuracy from 7037; to 8837; in a product attribute extraction task. We identify a saturation point of approximately 6500 samples beyond which additional data yields diminishing returns. Our proposed bayesian hyperparameter optimization method which evaluates models at 2037; of total training time correlates strongly with final model performance with 4 out of 5 top early45;stage models remaining in the top 5 at completion. This approach led to a 237; improvement in accuracy over baseline models when evaluated on an independent test set. These findings offer actionable insights for practitioners potentially reducing computational load and dependency on extensive datasets while enhancing overall performance of fine45;tuned LLMs.
