---
layout: publication
title: 'Correcting Large Language Model Behavior Via Influence Function'
authors: Han Zhang, Zhuo Zhang, Yi Zhang, Yuanzhao Zhai, Hanyang Peng, Yu Lei, Yue Yu, Hui Wang, Bin Liang, Lin Gui, Ruifeng Xu
conference: "Arxiv"
year: 2024
bibkey: zhang2024correcting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16451"}
tags: ['Interpretability and Explainability', 'Training Techniques', 'Efficiency and Optimization']
---
Recent advancements in AI alignment techniques have significantly improved
the alignment of large language models (LLMs) with static human preferences.
However, the dynamic nature of human preferences can render some prior training
data outdated or even erroneous, ultimately causing LLMs to deviate from
contemporary human preferences and societal norms. Existing methodologies,
whether they involve the curation of new data for continual alignment or the
manual correction of outdated data for re-alignment, demand costly human
resources. To address this challenge, we propose a novel approach, Large
Language Model Behavior Correction with Influence Function Recall and
Post-Training (LANCET), which requires no human involvement. LANCET consists of
two phases: (1) using influence functions to identify the training data that
significantly impact undesirable model outputs, and (2) applying an Influence
function-driven Bregman Optimization (IBO) technique to adjust the model's
behavior based on these influence distributions. Our experiments demonstrate
that LANCET effectively and efficiently correct inappropriate behaviors of
LLMs. Furthermore, LANCET can outperform methods that rely on collecting human
preferences, and it enhances the interpretability of learning human preferences
within LLMs.
