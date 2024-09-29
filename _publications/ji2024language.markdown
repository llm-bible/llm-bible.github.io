---
layout: publication
title: Language Models Resist Alignment
authors: Ji Jiaming, Wang Kaile, Qiu Tianyi, Chen Boyuan, Zhou Jiayi, Li Changye, Lou Hantao, Yang Yaodong
conference: "Arxiv"
year: 2024
bibkey: ji2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06144"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Large language models (LLMs) may exhibit undesirable behaviors. Recent efforts have focused on aligning these models to prevent harmful generation. Despite these efforts studies have shown that even a well-conducted alignment process can be easily circumvented whether intentionally or accidentally. Do alignment fine-tuning have robust effects on models or are merely superficial In this work we answer this question through both theoretical and empirical means. Empirically we demonstrate the elasticity of post-alignment models i.e. the tendency to revert to the behavior distribution formed during the pre-training phase upon further fine-tuning. Using compression theory we formally derive that such fine-tuning process disproportionately undermines alignment compared to pre-training potentially by orders of magnitude. We conduct experimental validations to confirm the presence of elasticity across models of varying types and sizes. Specifically we find that model performance declines rapidly before reverting to the pre-training distribution after which the rate of decline drops significantly. We further reveal that elasticity positively correlates with increased model size and the expansion of pre-training data. Our discovery signifies the importance of taming the inherent elasticity of LLMs thereby overcoming the resistance of LLMs to alignment finetuning.
