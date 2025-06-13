---
layout: publication
title: 'Boosting LLM Translation Skills Without General Ability Loss Via Rationale Distillation'
authors: Junhong Wu, Yang Zhao, Yangyifan Xu, Bing Liu, Chengqing Zong
conference: "Arxiv"
year: 2024
bibkey: wu2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13944"}
tags: ['Fine-Tuning', 'Responsible AI', 'Efficiency and Optimization', 'Applications', 'Security', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Large Language Models (LLMs) have achieved impressive results across numerous
NLP tasks but still encounter difficulties in machine translation. Traditional
methods to improve translation have typically involved fine-tuning LLMs using
parallel corpora. However, vanilla fine-tuning often leads to catastrophic
forgetting of the instruction-following capabilities and alignment with human
preferences, compromising their broad general abilities and introducing
potential security risks. These abilities, which are developed using
proprietary and unavailable training data, make existing continual instruction
tuning methods ineffective. To overcome this issue, we propose a novel approach
called RaDis (Rationale Distillation). RaDis harnesses the strong generative
capabilities of LLMs to create rationales for training data, which are then
"replayed" to prevent forgetting. These rationales encapsulate general
knowledge and safety principles, acting as self-distillation targets to
regulate the training process. By jointly training on both reference
translations and self-generated rationales, the model can learn new translation
skills while preserving its overall general abilities. Extensive experiments
demonstrate that our method enhances machine translation performance while
maintaining the broader capabilities of LLMs across other tasks. This work
presents a pathway for creating more versatile LLMs that excel in specialized
tasks without compromising generality and safety.
