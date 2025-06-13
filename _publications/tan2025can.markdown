---
layout: publication
title: 'Can Large Language Models Understand Preferences In Personalized Recommendation?'
authors: Zhaoxuan Tan, Zinan Zeng, Qingkai Zeng, Zhenyu Wu, Zheyuan Liu, Fengran Mo, Meng Jiang
conference: "Arxiv"
year: 2025
bibkey: tan2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.13391'}
  - {name: "Code", url: 'https://github.com/TamSiuhin/PerRecBench'}
tags: ['Has Code', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Ethics and Bias', 'Pretraining Methods']
---
Large Language Models (LLMs) excel in various tasks, including personalized
recommendations. Existing evaluation methods often focus on rating prediction,
relying on regression errors between actual and predicted ratings. However,
user rating bias and item quality, two influential factors behind rating
scores, can obscure personal preferences in user-item pair data. To address
this, we introduce PerRecBench, disassociating the evaluation from these two
factors and assessing recommendation techniques on capturing the personal
preferences in a grouped ranking manner. We find that the LLM-based
recommendation techniques that are generally good at rating prediction fail to
identify users' favored and disfavored items when the user rating bias and item
quality are eliminated by grouping users. With PerRecBench and 19 LLMs, we find
that while larger models generally outperform smaller ones, they still struggle
with personalized recommendation. Our findings reveal the superiority of
pairwise and listwise ranking approaches over pointwise ranking, PerRecBench's
low correlation with traditional regression metrics, the importance of user
profiles, and the role of pretraining data distributions. We further explore
three supervised fine-tuning strategies, finding that merging weights from
single-format training is promising but improving LLMs' understanding of user
preferences remains an open research problem. Code and data are available at
https://github.com/TamSiuhin/PerRecBench
