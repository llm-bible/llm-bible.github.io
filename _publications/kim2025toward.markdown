---
layout: publication
title: 'Toward Evaluative Thinking: Meta Policy Optimization With Evolving Reward Models'
authors: Zae Myung Kim, Chanwoo Park, Vipul Raheja, Suin Kim, Dongyeop Kang
conference: "Arxiv"
year: 2025
bibkey: kim2025toward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.20157'}
  - {name: "Code", url: 'https://github.com/minnesotanlp/mpo'}
tags: ['Has Code', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Reward-based alignment methods for large language models (LLMs) face two key limitations: vulnerability to reward hacking, where models exploit flaws in the reward signal; and reliance on brittle, labor-intensive prompt engineering when LLMs are used as reward models. We introduce Meta Policy Optimization (MPO), a framework that addresses these challenges by integrating a meta-reward model that dynamically refines the reward model's prompt throughout training. In MPO, the meta-reward model monitors the evolving training context and continuously adjusts the reward model's prompt to maintain high alignment, providing an adaptive reward signal that resists exploitation by the policy. This meta-learning approach promotes a more stable policy optimization, and greatly reduces the need for manual reward prompt design. It yields performance on par with or better than models guided by extensively hand-crafted reward prompts. Furthermore, we show that MPO maintains its effectiveness across diverse tasks, from essay writing to mathematical reasoning, without requiring specialized reward designs. Beyond standard RLAIF, MPO's meta-learning formulation is readily extensible to higher-level alignment frameworks. Overall, this method addresses theoretical and practical challenges in reward-based RL alignment for LLMs, paving the way for more robust and adaptable alignment strategies. The code and data can be accessed at: https://github.com/minnesotanlp/mpo
