---
layout: publication
title: 'Griffon-g: Bridging Vision-language And Vision-centric Tasks Via Large Multimodal Models'
authors: Yufei Zhan, Hongyin Zhao, Yousong Zhu, Fan Yang, Ming Tang, Jinqiao Wang
conference: "Arxiv"
year: 2024
bibkey: zhan2024griffon
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16163"}
tags: ['Applications', 'Training Techniques', 'Multimodal Models', 'Efficiency and Optimization']
---
Large Multimodal Models (LMMs) have achieved significant breakthroughs in
various vision-language and vision-centric tasks based on auto-regressive
modeling. However, these models typically focus on either vision-centric tasks,
such as visual grounding and region description, or vision-language tasks, like
image caption and multi-scenario VQAs. None of the LMMs have yet
comprehensively unified both types of tasks within a single model, as seen in
Large Language Models in the natural language processing field. Furthermore,
even with abundant multi-task instruction-following data, directly stacking
these data for universal capabilities extension remains challenging. To address
these issues, we introduce a novel multi-dimension curated and consolidated
multimodal dataset, named CCMD-8M, which overcomes the data barriers of
unifying vision-centric and vision-language tasks through multi-level data
curation and multi-task consolidation. More importantly, we present Griffon-G,
a general large multimodal model that addresses both vision-centric and
vision-language tasks within a single end-to-end paradigm. Griffon-G resolves
the training collapse issue encountered during the joint optimization of these
tasks, achieving better training efficiency. Evaluations across multimodal
benchmarks, general Visual Question Answering (VQA) tasks, scene text-centric
VQA tasks, document-related VQA tasks, Referring Expression Comprehension, and
object detection demonstrate that Griffon-G surpasses the advanced LMMs and
achieves expert-level performance in complicated vision-centric tasks.
