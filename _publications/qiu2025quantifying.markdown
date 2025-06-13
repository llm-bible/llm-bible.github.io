---
layout: publication
title: 'Quantifying The Reasoning Abilities Of Llms On Real-world Clinical Cases'
authors: Pengcheng Qiu, Chaoyi Wu, Shuyu Liu, Weike Zhao, Zhuoxia Chen, Hongfei Gu, Chuanjin Peng, Ya Zhang, Yanfeng Wang, Weidi Xie
conference: "Arxiv"
year: 2025
bibkey: qiu2025quantifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04691'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Tools']
---
Recent advancements in reasoning-enhanced large language models (LLMs), such
as DeepSeek-R1 and OpenAI-o3, have demonstrated significant progress. However,
their application in professional medical contexts remains underexplored,
particularly in evaluating the quality of their reasoning processes alongside
final outputs. Here, we introduce MedR-Bench, a benchmarking dataset of 1,453
structured patient cases, annotated with reasoning references derived from
clinical case reports. Spanning 13 body systems and 10 specialties, it includes
both common and rare diseases. To comprehensively evaluate LLM performance, we
propose a framework encompassing three critical examination recommendation,
diagnostic decision-making, and treatment planning, simulating the entire
patient care journey. To assess reasoning quality, we present the Reasoning
Evaluator, a novel automated system that objectively scores free-text reasoning
responses based on efficiency, actuality, and completeness using dynamic
cross-referencing and evidence checks. Using this benchmark, we evaluate five
state-of-the-art reasoning LLMs, including DeepSeek-R1, OpenAI-o3-mini, and
Gemini-2.0-Flash Thinking, etc. Our results show that current LLMs achieve over
85% accuracy in relatively simple diagnostic tasks when provided with
sufficient examination results. However, performance declines in more complex
tasks, such as examination recommendation and treatment planning. While
reasoning outputs are generally reliable, with factuality scores exceeding 90%,
critical reasoning steps are frequently missed. These findings underscore both
the progress and limitations of clinical LLMs. Notably, open-source models like
DeepSeek-R1 are narrowing the gap with proprietary systems, highlighting their
potential to drive accessible and equitable advancements in healthcare.
