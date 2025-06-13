---
layout: publication
title: 'An Empirical Study Of Data Ability Boundary In Llms'' Math Reasoning'
authors: Zui Chen, Yezeng Chen, Jiaqi Han, Zhijie Huang, Ji Qi, Yi Zhou
conference: "Arxiv"
year: 2024
bibkey: chen2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00799"}
  - {name: "Code", url: "https://github.com/cyzhh/MMOS"}
tags: ['Fine-Tuning', 'Applications', 'Model Architecture', 'Security', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Large language models (LLMs) are displaying emergent abilities for math
reasoning tasks,and there is a growing attention on enhancing the ability of
open-source LLMs through supervised fine-tuning (SFT).In this paper, we aim to
explore a general data strategy for supervised data to help optimize and expand
math reasoning ability.Firstly, we determine the ability boundary of reasoning
paths augmentation by identifying these paths' minimal optimal set.Secondly, we
validate that different abilities of the model can be cumulatively enhanced by
Mix of Minimal Optimal Sets of corresponding types of data, while our models
MMOS achieve SOTA performance on series base models under much lower
construction costs.Besides, we point out GSM-HARD is not really hard and
today's LLMs no longer lack numerical robustness.Also, we provide an Auto
Problem Generator for robustness testing and educational applications.Our code
and data are publicly available at https://github.com/cyzhh/MMOS.
