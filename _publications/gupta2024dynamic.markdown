---
layout: publication
title: 'CARMO: Dynamic Criteria Generation For Context-aware Reward Modelling'
authors: Taneesh Gupta, Shivam Shandilya, Xuchao Zhang, Rahul Madhavan, Supriyo Ghosh, Chetan Bansal, Huaxiu Yao, Saravan Rajmohan
conference: "Arxiv"
year: 2024
bibkey: gupta2024dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21545'}
tags: ['Reinforcement Learning', 'RAG', 'Agentic', 'Training Techniques']
---
Reward modeling in large language models is susceptible to reward hacking,
causing models to latch onto superficial features such as the tendency to
generate lists or unnecessarily long responses. In reinforcement learning from
human feedback (RLHF) and more generally during post-training flawed reward
signals often lead to outputs that optimize for these spurious correlates
instead of genuine quality or correctness. We propose Context-Aware Reward
Modeling (CARMO), a novel approach that first generates dynamic,
context-relevant criteria to ground the reward model before producing reward
scores. Unlike prior methods that rely on static rubrics, CARMO leverages large
language models (LLMs) to adaptively create evaluation criteria such as logical
consistency, clarity, and depth tailored to the user query. Our theoretical
analysis shows that such criteria generation can mitigate reward hacking. We
further demonstrate that CARMO can be distilled into smaller models, reducing
the computational cost of alignment. We establish a new state-of-the-art
performance in zero-shot settings for generative models, achieving a 2.1%
improvement on Reward Bench. Furthermore, alignment performed on the
CARMO-curated preference dataset achieves 22.5% and 21.1% LC-WR and WR,
respectively, on Mistral-Base (7B).
