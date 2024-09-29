---
layout: publication
title: "Robust Preference Learning For Storytelling Via Contrastive Reinforcement Learning"
authors: Castricato Louis, Havrilla Alexander, Matiana Shahbuland, Pieler Michael, Ye Anbang, Yang Ian, Frazier Spencer, Riedl Mark
conference: "Arxiv"
year: 2022
bibkey: castricato2022robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.07792"}
tags: ['Agentic', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Controlled automated story generation seeks to generate natural language stories satisfying constraints from natural language critiques or preferences. Existing methods to control for story preference utilize prompt engineering which is labor intensive and often inconsistent. They may also use logit-manipulation methods which require annotated datasets to exist for the desired attributes. To address these issues we first train a contrastive bi-encoder model to align stories with corresponding human critiques named CARP building a general purpose preference model. This is subsequently used as a reward function to fine-tune a generative language model via reinforcement learning. However simply fine-tuning a generative language model with a contrastive reward model does not always reliably result in a story generation system capable of generating stories that meet user preferences. To increase story generation robustness we further fine-tune the contrastive reward model using a prompt-learning technique. A human participant study is then conducted comparing generations from our full system ablations and two baselines. We show that the full fine-tuning pipeline results in a story generator preferred over a LLM 20x as large as well as logit-based methods. This motivates the use of contrastive learning for general purpose human preference modeling.
