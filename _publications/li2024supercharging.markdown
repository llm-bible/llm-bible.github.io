---
layout: publication
title: 'Llara: Supercharging Robot Learning Data For Vision-language Policy'
authors: Xiang Li, Cristina Mata, Jongwoo Park, Kumara Kahatapitiya, Yoo Sung Jang, Jinghuan Shang, Kanchana Ranasinghe, Ryan Burgert, Mu Cai, Yong Jae Lee, Michael S. Ryoo
conference: "Arxiv"
year: 2024
bibkey: li2024supercharging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.20095'}
  - {name: "Code", url: 'https://github.com/LostXine/LLaRA'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Tools', 'Multimodal Models', 'Reinforcement Learning']
---
Vision Language Models (VLMs) have recently been leveraged to generate
robotic actions, forming Vision-Language-Action (VLA) models. However, directly
adapting a pretrained VLM for robotic control remains challenging, particularly
when constrained by a limited number of robot demonstrations. In this work, we
introduce LLaRA: Large Language and Robotics Assistant, a framework that
formulates robot action policy as visuo-textual conversations and enables an
efficient transfer of a pretrained VLM into a powerful VLA, motivated by the
success of visual instruction tuning in Computer Vision. First, we present an
automated pipeline to generate conversation-style instruction tuning data for
robots from existing behavior cloning datasets, aligning robotic actions with
image pixel coordinates. Further, we enhance this dataset in a self-supervised
manner by defining six auxiliary tasks, without requiring any additional action
annotations. We show that a VLM finetuned with a limited amount of such
datasets can produce meaningful action decisions for robotic control. Through
experiments across multiple simulated and real-world tasks, we demonstrate that
LLaRA achieves state-of-the-art performance while preserving the generalization
capabilities of large language models. The code, datasets, and pretrained
models are available at https://github.com/LostXine/LLaRA.
