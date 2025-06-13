---
layout: publication
title: 'Adarewriter: Unleashing The Power Of Prompting-based Conversational Query Reformulation Via Test-time Adaptation'
authors: Yilong Lai, Jialong Wu, Zhenglin Wang, Deyu Zhou
conference: "Arxiv"
year: 2025
bibkey: lai2025unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01381"}
tags: ['Prompting', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Prompting-based conversational query reformulation has emerged as a powerful approach for conversational search, refining ambiguous user queries into standalone search queries. Best-of-N reformulation over the generated candidates via prompting shows impressive potential scaling capability. However, both the previous tuning methods (training time) and adaptation approaches (test time) can not fully unleash their benefits. In this paper, we propose AdaRewriter, a novel framework for query reformulation using an outcome-supervised reward model via test-time adaptation. By training a lightweight reward model with contrastive ranking loss, AdaRewriter selects the most promising reformulation during inference. Notably, it can operate effectively in black-box systems, including commercial LLM APIs. Experiments on five conversational search datasets show that AdaRewriter significantly outperforms the existing methods across most settings, demonstrating the potential of test-time adaptation for conversational query reformulation.
