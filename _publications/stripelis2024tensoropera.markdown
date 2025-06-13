---
layout: publication
title: 'Tensoropera Router: A Multi-model Router For Efficient LLM Inference'
authors: Dimitris Stripelis, Zijian Hu, Jipeng Zhang, Zhaozhuo Xu, Alay Dilipbhai Shah, Han Jin, Yuhang Yao, Salman Avestimehr, Chaoyang He
conference: "Arxiv"
year: 2024
bibkey: stripelis2024tensoropera
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.12320'}
tags: ['Efficiency and Optimization', 'Tools']
---
With the rapid growth of Large Language Models (LLMs) across various domains,
numerous new LLMs have emerged, each possessing domain-specific expertise. This
proliferation has highlighted the need for quick, high-quality, and
cost-effective LLM query response methods. Yet, no single LLM exists to
efficiently balance this trilemma. Some models are powerful but extremely
costly, while others are fast and inexpensive but qualitatively inferior. To
address this challenge, we present TO-Router, a non-monolithic LLM querying
system that seamlessly integrates various LLM experts into a single query
interface and dynamically routes incoming queries to the most high-performant
expert based on query's requirements. Through extensive experiments, we
demonstrate that when compared to standalone expert models, TO-Router improves
query efficiency by up to 40%, and leads to significant cost reductions of up
to 30%, while maintaining or enhancing model performance by up to 10%.
