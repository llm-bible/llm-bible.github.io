---
layout: publication
title: 'VLM Q-learning: Aligning Vision-language Models For Interactive Decision-making'
authors: Jake Grigsby, Yuke Zhu, Michael Ryoo, Juan Carlos Niebles
conference: "Arxiv"
year: 2025
bibkey: grigsby2025vlm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03181"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Recent research looks to harness the general knowledge and reasoning of large
language models (LLMs) into agents that accomplish user-specified goals in
interactive environments. Vision-language models (VLMs) extend LLMs to
multi-modal data and provide agents with the visual reasoning necessary for new
applications in areas such as computer automation. However, agent tasks
emphasize skills where accessible open-weight VLMs lag behind their LLM
equivalents. For example, VLMs are less capable of following an environment's
strict output syntax requirements and are more focused on open-ended question
answering. Overcoming these limitations requires supervised fine-tuning (SFT)
on task-specific expert demonstrations. Our work approaches these challenges
from an offline-to-online reinforcement learning (RL) perspective. RL lets us
fine-tune VLMs to agent tasks while learning from the unsuccessful decisions of
our own model or more capable (larger) models. We explore an off-policy RL
solution that retains the stability and simplicity of the widely used SFT
workflow while allowing our agent to self-improve and learn from low-quality
datasets. We demonstrate this technique with two open-weight VLMs across three
multi-modal agent domains.
