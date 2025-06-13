---
layout: publication
title: 'CLEAN-EVAL: Clean Evaluation On Contaminated Large Language Models'
authors: Wenhong Zhu, Hongkun Hao, Zhiwei He, Yunze Song, Yumeng Zhang, Hanxu Hu, Yiran Wei, Rui Wang, Hongyuan Lu
conference: "Arxiv"
year: 2023
bibkey: zhu2023clean
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.09154'}
tags: ['Few-Shot', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
We are currently in an era of fierce competition among various large language
models (LLMs) continuously pushing the boundaries of benchmark performance.
However, genuinely assessing the capabilities of these LLMs has become a
challenging and critical issue due to potential data contamination, and it
wastes dozens of time and effort for researchers and engineers to download and
try those contaminated models. To save our precious time, we propose a novel
and useful method, Clean-Eval, which mitigates the issue of data contamination
and evaluates the LLMs in a cleaner manner. Clean-Eval employs an LLM to
paraphrase and back-translate the contaminated data into a candidate set,
generating expressions with the same meaning but in different surface forms. A
semantic detector is then used to filter the generated low-quality samples to
narrow down this candidate set. The best candidate is finally selected from
this set based on the BLEURT score. According to human assessment, this best
candidate is semantically similar to the original contamination data but
expressed differently. All candidates can form a new benchmark to evaluate the
model. Our experiments illustrate that Clean-Eval substantially restores the
actual evaluation results on contaminated LLMs under both few-shot learning and
fine-tuning scenarios.
