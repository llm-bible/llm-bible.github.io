---
layout: publication
title: 'Training-free Mitigation Of Language Reasoning Degradation After Multimodal Instruction Tuning'
authors: Neale Ratzlaff, Man Luo, Xin Su, Vasudev Lal, Phillip Howard
conference: "Arxiv"
year: 2024
bibkey: ratzlaff2024training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.03467'}
tags: ['Multimodal Models', 'Tools', 'Training Techniques', 'Merging']
---
Multimodal models typically combine a powerful large language model (LLM)
with a vision encoder and are then trained on multimodal data via instruction
tuning. While this process adapts LLMs to multimodal settings, it remains
unclear whether this adaptation compromises their original language reasoning
capabilities. In this work, we explore the effects of multimodal instruction
tuning on language reasoning performance. We focus on LLaVA, a leading
multimodal framework that integrates LLMs such as Vicuna or Mistral with the
CLIP vision encoder. We compare the performance of the original LLMs with their
multimodal-adapted counterparts across eight language reasoning tasks. Our
experiments yield several key insights. First, the impact of multimodal
learning varies between Vicuna and Mistral: we observe a degradation in
language reasoning for Mistral but improvements for Vicuna across most tasks.
Second, while multimodal instruction learning consistently degrades performance
on mathematical reasoning tasks (e.g., GSM8K), it enhances performance on
commonsense reasoning tasks (e.g., CommonsenseQA). Finally, we demonstrate that
a training-free model merging technique can effectively mitigate the language
reasoning degradation observed in multimodal-adapted Mistral and even improve
performance on visual tasks.
