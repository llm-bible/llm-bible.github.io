---
layout: publication
title: Selective Reflection-Tuning Student-Selected Data Recycling for LLM Instruction-Tuning
authors: Li Ming, Chen Lichang, Chen Jiuhai, He Shwai, Gu Jiuxiang, Zhou Tianyi
conference: "Arxiv"
year: 2024
bibkey: li2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10110"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Reinforcement Learning', 'Training Techniques']
---
Instruction tuning is critical to large language models (LLMs) for achieving better instruction following and task adaptation capabilities but its success heavily relies on the training data quality. Many recent methods focus on improving the data quality but often overlook the compatibility of the data with the student model being finetuned. This paper introduces Selective Reflection-Tuning a novel paradigm that synergizes a teacher LLMs reflection and introspection for improving existing data quality with the data selection capability of the student LLM to automatically refine existing instruction-tuning data. This teacher-student collaboration produces high-quality and student-compatible instruction-response pairs resulting in sample-efficient instruction tuning and LLMs of superior performance. Selective Reflection-Tuning is a data augmentation and synthesis that generally improves LLM finetuning and self-improvement without collecting brand-new data. We apply our method to Alpaca and WizardLM data and achieve much stronger and top-tier 7B and 13B LLMs.
