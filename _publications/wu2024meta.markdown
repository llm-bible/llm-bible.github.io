---
layout: publication
title: Meta-Rewarding Language Models Self-Improving Alignment with LLM-as-a-Meta-Judge
authors: Wu Tianhao, Yuan Weizhe, Golovneva Olga, Xu Jing, Tian Yuandong, Jiao Jiantao, Weston Jason, Sukhbaatar Sainbayar
conference: "Arxiv"
year: 2024
bibkey: wu2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19594"}
tags: ['Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) are rapidly surpassing human knowledge in many domains. While improving these models traditionally relies on costly human data recent self-rewarding mechanisms (Yuan et al. 2024) have shown that LLMs can improve by judging their own responses instead of relying on human labelers. However existing methods have primarily focused on improving model responses rather than judgment capabilities resulting in rapid saturation during iterative training. To address this issue we introduce a novel Meta-Rewarding step to the self-improvement process where the model judges its own judgements and uses that feedback to refine its judgment skills. Surprisingly this unsupervised approach improves the models ability to judge em and follow instructions as demonstrated by a win rate improvement of Llama-3-8B-Instruct from 22.9 to 39.4 on AlpacaEval 2 and 20.6 to 29.1 on Arena-Hard. These results strongly suggest the potential for self-improving models without human supervision.
