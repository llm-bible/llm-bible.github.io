---
layout: publication
title: 'Embodiedeval: Evaluate Multimodal Llms As Embodied Agents'
authors: Zhili Cheng, Yuge Tu, Ran Li, Shiqi Dai, Jinyi Hu, Shengding Hu, Jiahao Li, Yang Shi, Tianyu Yu, Weize Chen, Lei Shi, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: cheng2025evaluate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.11858"}
  - {name: "Code", url: "https://github.com/thunlp/EmbodiedEval"}
tags: ['Agentic', 'Tools', 'Applications', 'Has Code', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) have shown significant advancements,
providing a promising future for embodied agents. Existing benchmarks for
evaluating MLLMs primarily utilize static images or videos, limiting
assessments to non-interactive scenarios. Meanwhile, existing embodied AI
benchmarks are task-specific and not diverse enough, which do not adequately
evaluate the embodied capabilities of MLLMs. To address this, we propose
EmbodiedEval, a comprehensive and interactive evaluation benchmark for MLLMs
with embodied tasks. EmbodiedEval features 328 distinct tasks within 125 varied
3D scenes, each of which is rigorously selected and annotated. It covers a
broad spectrum of existing embodied AI tasks with significantly enhanced
diversity, all within a unified simulation and evaluation framework tailored
for MLLMs. The tasks are organized into five categories: navigation, object
interaction, social interaction, attribute question answering, and spatial
question answering to assess different capabilities of the agents. We evaluated
the state-of-the-art MLLMs on EmbodiedEval and found that they have a
significant shortfall compared to human level on embodied tasks. Our analysis
demonstrates the limitations of existing MLLMs in embodied capabilities,
providing insights for their future development. We open-source all evaluation
data and simulation framework at https://github.com/thunlp/EmbodiedEval.
