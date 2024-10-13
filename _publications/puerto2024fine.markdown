---
layout: publication
title: 'Fine-tuning With Divergent Chains Of Thought Boosts Reasoning Through Self-correction In Language Models'
authors: Puerto Haritz, Chubakov Tilek, Zhu Xiaodan, Madabushi Harish Tayyar, Gurevych Iryna
conference: "Arxiv"
year: 2024
bibkey: puerto2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03181"}
  - {name: "Code", url: "https://github.com/UKPLab/arxiv2024-divergent-cot"}
tags: ['Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
Requiring a Large Language Model to generate intermediary reasoning steps has
been shown to be an effective way of boosting performance. In fact, it has been
found that instruction tuning on these intermediary reasoning steps improves
model performance. In this work, we present a novel method of further improving
performance by requiring models to compare multiple reasoning chains before
generating a solution in a single inference step. We call this method Divergent
CoT (DCoT). We find that instruction tuning on DCoT datasets boosts the
performance of even smaller, and therefore more accessible, LLMs. Through a
rigorous set of experiments spanning a wide range of tasks that require various
reasoning types, we show that fine-tuning on DCoT consistently improves
performance over the CoT baseline across model families and scales (1.3B to
70B). Through a combination of empirical and manual evaluation, we additionally
show that these performance gains stem from models generating multiple
divergent reasoning chains in a single inference step, indicative of the
enabling of self-correction in language models. Our code and data are publicly
available at https://github.com/UKPLab/arxiv2024-divergent-cot.
