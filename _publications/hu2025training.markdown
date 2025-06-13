---
layout: publication
title: 'Training An Llm-as-a-judge Model: Pipeline, Insights, And Practical Lessons'
authors: Renjun Hu, Yi Cheng, Libin Meng, Jiaxin Xia, Yi Zong, Xing Shi, Wei Lin
conference: "Arxiv"
year: 2025
bibkey: hu2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02988'}
tags: ['Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
The rapid advancement of large language models (LLMs) has opened new
possibilities for their adoption as evaluative judges. This paper introduces
Themis, a fine-tuned LLM judge that delivers sophisticated context-aware
evaluations. We provide a comprehensive overview of the development pipeline
for Themis, highlighting its scenario-dependent evaluation prompts and two
novel methods for controlled instruction generation. These designs enable
Themis to effectively distill evaluative skills from teacher models, while
retaining flexibility for continuous development. We introduce two
human-labeled benchmarks for meta-evaluation, demonstrating that Themis can
achieve high alignment with human preferences in an economical manner.
Additionally, we explore insights into the LLM-as-a-judge paradigm, revealing
nuances in performance and the varied effects of reference answers. Notably, we
observe that pure knowledge distillation from strong LLMs, though common, does
not guarantee performance improvement through scaling. We propose a mitigation
strategy based on instruction-following difficulty. Furthermore, we provide
practical guidelines covering data balancing, prompt customization,
multi-objective training, and metric aggregation. We aim for our method and
findings, along with the fine-tuning data, benchmarks, and model checkpoints,
to support future research and development in this area.
