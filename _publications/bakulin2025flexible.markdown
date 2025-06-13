---
layout: publication
title: 'FLAME: Flexible Llm-assisted Moderation Engine'
authors: Ivan 1 And 2 Bakulin, Ilia 1 And 2 Kopanichuk, Iaroslav 1 And 4 Bespalov, Nikita 1 And 4 Radchenko, Vladimir 1 And 4 Shaposhnikov, Dmitry 1 And 4 Dylov, Ivan 1 And 4 Oseledets
conference: "Arxiv"
year: 2025
bibkey: bakulin2025flexible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.09175'}
tags: ['Efficiency and Optimization', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Reinforcement Learning', 'Responsible AI']
---
The rapid advancement of Large Language Models (LLMs) has introduced
significant challenges in moderating user-model interactions. While LLMs
demonstrate remarkable capabilities, they remain vulnerable to adversarial
attacks, particularly ``jailbreaking'' techniques that bypass content safety
measures. Current content moderation systems, which primarily rely on input
prompt filtering, have proven insufficient, with techniques like Best-of-N
(BoN) jailbreaking achieving success rates of 80% or more against popular LLMs.
In this paper, we introduce Flexible LLM-Assisted Moderation Engine (FLAME): a
new approach that shifts the focus from input filtering to output moderation.
Unlike traditional circuit-breaking methods that analyze user queries, FLAME
evaluates model responses, offering several key advantages: (1) computational
efficiency in both training and inference, (2) enhanced resistance to BoN
jailbreaking attacks, and (3) flexibility in defining and updating safety
criteria through customizable topic filtering. Our experiments demonstrate that
FLAME significantly outperforms current moderation systems. For example, FLAME
reduces attack success rate in GPT-4o-mini and DeepSeek-v3 by a factor of ~9,
while maintaining low computational overhead. We provide comprehensive
evaluation on various LLMs and analyze the engine's efficiency against the
state-of-the-art jailbreaking. This work contributes to the development of more
robust and adaptable content moderation systems for LLMs.
