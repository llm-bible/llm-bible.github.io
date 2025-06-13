---
layout: publication
title: 'Language Models Resist Alignment: Evidence From Data Compression'
authors: Jiaming Ji, Kaile Wang, Tianyi Qiu, Boyuan Chen, Jiayi Zhou, Changye Li, Hantao Lou, Josef Dai, Yunhuai Liu, Yaodong Yang
conference: "Arxiv"
year: 2024
bibkey: ji2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06144"}
tags: ['Fine-Tuning', 'Pre-Training', 'Tools', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) may exhibit unintended or undesirable behaviors.
Recent works have concentrated on aligning LLMs to mitigate harmful outputs.
Despite these efforts, some anomalies indicate that even a well-conducted
alignment process can be easily circumvented, whether intentionally or
accidentally. Does alignment fine-tuning yield have robust effects on models,
or are its impacts merely superficial? In this work, we make the first
exploration of this phenomenon from both theoretical and empirical
perspectives. Empirically, we demonstrate the elasticity of post-alignment
models, i.e., the tendency to revert to the behavior distribution formed during
the pre-training phase upon further fine-tuning. Leveraging compression theory,
we formally deduce that fine-tuning disproportionately undermines alignment
relative to pre-training, potentially by orders of magnitude. We validate the
presence of elasticity through experiments on models of varying types and
scales. Specifically, we find that model performance declines rapidly before
reverting to the pre-training distribution, after which the rate of decline
drops significantly. Furthermore, we further reveal that elasticity positively
correlates with the increased model size and the expansion of pre-training
data. Our findings underscore the need to address the inherent elasticity of
LLMs to mitigate their resistance to alignment.
