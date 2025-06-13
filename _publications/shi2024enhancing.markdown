---
layout: publication
title: 'Enhancing Video-llm Reasoning Via Agent-of-thoughts Distillation'
authors: Yudi Shi, Shangzhe Di, Qirui Chen, Weidi Xie
conference: "Arxiv"
year: 2024
bibkey: shi2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01694"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Applications', 'Interpretability and Explainability', 'RAG', 'Interpretability', 'Distillation']
---
This paper tackles the problem of video question answering (VideoQA), a task
that often requires multi-step reasoning and a profound understanding of
spatial-temporal dynamics. While large video-language models perform well on
benchmarks, they often lack explainability and spatial-temporal grounding. In
this paper, we propose Agent-of-Thoughts Distillation (AoTD), a method that
enhances models by incorporating automatically generated Chain-of-Thoughts
(CoTs) into the instruction-tuning process. Specifically, we leverage an
agent-based system to decompose complex questions into sub-tasks, and address
them with specialized vision models, the intermediate results are then treated
as reasoning chains. We also introduce a verification mechanism using a large
language model (LLM) to ensure the reliability of generated CoTs. Extensive
experiments demonstrate that AoTD improves the performance on multiple-choice
and open-ended benchmarks.
