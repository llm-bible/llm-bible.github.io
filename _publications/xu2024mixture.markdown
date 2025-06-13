---
layout: publication
title: 'Mixture-of-instructions: Aligning Large Language Models Via Mixture Prompting'
authors: Bowen Xu, Shaoyu Wu, Kai Liu, Lulu Hu
conference: "Arxiv"
year: 2024
bibkey: xu2024mixture
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.18410'}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Prompting', 'Training Techniques']
---
With the proliferation of large language models (LLMs), the comprehensive
alignment of such models across multiple tasks has emerged as a critical area
of research. Existing alignment methodologies primarily address single task,
such as multi-turn dialogue, coding, mathematical problem-solving, and tool
usage. Although there is a large amount of high-quality data available for
those tasks, most of them provide only questions and answers without including
the system prompt. Though a detailed analysis of the Qwen language model, we
found that the system prompt has a significant impact on both training and
inference processes of LLM. We attributes this phenomenon to overfitting to the
system prompt. In address this issue, we introduce a novel technique termed
Mixture-of-Instructions (MoI), which employs a strategy of instruction packing
combined with diverse system prompts to boost the alignment efficiency of
language models. We have also compiled a diverse set of seven benchmark
datasets to rigorously evaluate the alignment efficacy of the MoI-enhanced
language model. Our methodology was applied to the open-source Qwen-7B-chat
model, culminating in the development of Qwen-SFT-MoI. This enhanced model
demonstrates significant advancements in generative capabilities across coding,
mathematics, and tool use tasks.
