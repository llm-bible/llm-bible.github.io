---
layout: publication
title: 'Supercorrect: Advancing Small LLM Reasoning With Thought Template Distillation And Self-correction'
authors: Ling Yang, Zhaochen Yu, Tianjun Zhang, Minkai Xu, Joseph E. Gonzalez, Bin Cui, Shuicheng Yan
conference: "Arxiv"
year: 2024
bibkey: yang2024advancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.09008'}
  - {name: "Code", url: 'https://github.com/YangLing0818/SuperCorrect-llm'}
tags: ['Has Code', 'Efficiency and Optimization', 'Distillation', 'Model Architecture', 'Training Techniques', 'Tools', 'GPT', 'Reinforcement Learning']
---
Large language models (LLMs) like GPT-4, DeepSeek-R1, and ReasonFlux have
shown significant improvements in various reasoning tasks. However, smaller
LLMs still struggle with complex mathematical reasoning because they fail to
effectively identify and correct reasoning errors. Recent reflection-based
methods aim to address these issues by enabling self-reflection and
self-correction, but they still face challenges in independently detecting
errors in their reasoning steps. To overcome these limitations, we propose
SuperCorrect, a novel two-stage framework that uses a large teacher model to
supervise and correct both the reasoning and reflection processes of a smaller
student model. In the first stage, we extract hierarchical high-level and
detailed thought templates from the teacher model to guide the student model in
eliciting more fine-grained reasoning thoughts. In the second stage, we
introduce cross-model collaborative direct preference optimization (DPO) to
enhance the self-correction abilities of the student model by following the
teacher's correction traces during training. This cross-model DPO approach
teaches the student model to effectively locate and resolve erroneous thoughts
with error-driven insights from the teacher model, breaking the bottleneck of
its thoughts and acquiring new skills and knowledge to tackle challenging
problems. Extensive experiments consistently demonstrate our superiority over
previous methods. Notably, our SuperCorrect-7B model significantly surpasses
powerful DeepSeekMath-7B by 7.8%/5.3% and Qwen2.5-Math-7B by 15.1%/6.3% on
MATH/GSM8K benchmarks, achieving new SOTA performance among all 7B models.
Code: https://github.com/YangLing0818/SuperCorrect-llm
