---
layout: publication
title: 'Come: An Unlearning-based Approach To Conflict-free Model Editing'
authors: Dahyun Jung, Jaehyung Seo, Jaewook Lee, Chanjun Park, Heuiseok Lim
conference: "Arxiv"
year: 2025
bibkey: jung2025unlearning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15826"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Pre-Training']
---
Large language models (LLMs) often retain outdated or incorrect information
from pre-training, which undermines their reliability. While model editing
methods have been developed to address such errors without full re-training,
they frequently suffer from knowledge conflicts, where outdated information
interferes with new knowledge. In this work, we propose Conflict-free Model
Editing (CoME), a novel framework that enhances the accuracy of knowledge
updates in LLMs by selectively removing outdated knowledge. CoME leverages
unlearning to mitigate knowledge interference, allowing new information to be
integrated without compromising relevant linguistic features. Through
experiments on GPT-J and LLaMA-3 using Counterfact and ZsRE datasets, we
demonstrate that CoME improves both editing accuracy and model reliability when
applied to existing editing methods. Our results highlight that the targeted
removal of outdated knowledge is crucial for enhancing model editing
effectiveness and maintaining the model's generative performance.
