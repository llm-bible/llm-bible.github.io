---
layout: publication
title: 'P3: A Policy-driven, Pace-adaptive, And Diversity-promoted Framework For Data Pruning In LLM Training'
authors: Yingxuan Yang, Huayi Wang, Muning Wen, Xiaoyun Mo, Qiuying Peng, Jun Wang, Weinan Zhang
conference: "Arxiv"
year: 2024
bibkey: yang2024policy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.05541"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Training Techniques', 'Pretraining Methods']
---
In the rapidly advancing field of Large Language Models (LLMs), effectively
leveraging existing datasets during fine-tuning to maximize the model's
potential is of paramount importance. This paper introduces P3, an adaptive
framework aimed at optimizing the task-specific fine-tuning process through
iterative data pruning. P3 consists of three key components: (1) Policy-driven
Difficulty Measurement, which dynamically assesses data difficulty based on the
model's real-time performance, replacing static metrics with adaptable
evaluations; (2) Pace-Adaptive Selection, leveraging self-paced learning to
progressively introduce more challenging data, thereby enhancing model
capability; (3) Diversity Promotion, incorporating Determinantal Point Process
(DPP) to ensure data diversity across epochs, enriching the learning process.
We validate P3 on the reasoning scenarios, APPS and MATH, demonstrating
significant improvements over traditional data pruning methods. By advancing
dynamic data selection and utilization strategies, P3 contributes both a
theoretical framework and concrete approach to fully exploit existing data for
LLMs' performance improvement, offering utility across diverse tasks.
