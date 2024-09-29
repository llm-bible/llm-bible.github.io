---
layout: publication
title: "Create Your World: Lifelong Text-to-image Diffusion"
authors: Sun Gan, Liang Wenqi, Dong Jiahua, Li Jun, Ding Zhengming, Cong Yang
conference: "Arxiv"
year: 2023
bibkey: sun2023create
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04430"}
  - {name: "Code", url: "https://wenqiliang.github.io/"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Merging', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Text-to-image generative models can produce diverse high-quality images of concepts with a text prompt which have demonstrated excellent ability in image generation image translation etc. We in this work study the problem of synthesizing instantiations of a uses own concepts in a never-ending manner i.e. create your world where the new concepts from user are quickly learned with a few examples. To achieve this goal we propose a Lifelong text-to-image Diffusion Model (L2DM) which intends to overcome knowledge catastrophic forgetting for the past encountered concepts and semantic catastrophic neglecting for one or more concepts in the text prompt. In respect of knowledge catastrophic forgetting our L2DM framework devises a task-aware memory enhancement module and a elastic-concept distillation module which could respectively safeguard the knowledge of both prior concepts and each past personalized concept. When generating images with a user text prompt the solution to semantic catastrophic neglecting is that a concept attention artist module can alleviate the semantic neglecting from concept aspect and an orthogonal attention module can reduce the semantic binding from attribute aspect. To the end our model can generate more faithful image across a range of continual text prompts in terms of both qualitative and quantitative metrics when comparing with the related state-of-the-art models. The code will be released at https://wenqiliang.github.io/."
