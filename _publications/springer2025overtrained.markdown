---
layout: publication
title: 'Overtrained Language Models Are Harder To Fine-tune'
authors: Jacob Mitchell Springer, Sachin Goyal, Kaiyue Wen, Tanishq Kumar, Xiang Yue, Sadhika Malladi, Graham Neubig, Aditi Raghunathan
conference: "Arxiv"
year: 2025
bibkey: springer2025overtrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19206"}
tags: ['Pretraining Methods', 'Training Techniques', 'Pre-Training', 'Fine-Tuning']
---
Large language models are pre-trained on ever-growing token budgets under the
assumption that better pre-training performance translates to improved
downstream models. In this work, we challenge this assumption and show that
extended pre-training can make models harder to fine-tune, leading to degraded
final performance. We term this phenomenon catastrophic overtraining. For
example, the instruction-tuned OLMo-1B model pre-trained on 3T tokens leads to
over 2% worse performance on multiple standard LLM benchmarks than its 2.3T
token counterpart. Through controlled experiments and theoretical analysis, we
show that catastrophic overtraining arises from a systematic increase in the
broad sensitivity of pre-trained parameters to modifications, including but not
limited to fine-tuning. Our findings call for a critical reassessment of
pre-training design that considers the downstream adaptability of the model.
