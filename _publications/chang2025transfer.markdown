---
layout: publication
title: 'Transfer-prompting: Enhancing Cross-task Adaptation In Large Language Models Via Dual-stage Prompts Optimization'
authors: Yupeng Chang, Yi Chang, Yuan Wu
conference: "Arxiv"
year: 2025
bibkey: chang2025transfer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14211'}
  - {name: "Code", url: 'https://github.com/llm172/Transfer-Prompting'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) face significant challenges when balancing
multiple high-level objectives, such as generating coherent, relevant, and
high-quality responses while maintaining efficient task adaptation across
diverse tasks. To address these challenges, we introduce Transfer-Prompting, a
novel two-stage framework designed to enhance cross-task adaptation in prompt
generation. The framework comprises two key components: (1) source prompt
construction, which refines the original prompts on source task datasets to
generate source prompts with enhanced generalization ability, and (2) target
prompt generation, which enhances cross-task adaptation of target prompts by
fine-tuning a set of high-scored source prompts on task-specific datasets. In
each optimization cycle, a reference LLM generates candidate prompts based on
historical prompt-score pairs and task descriptions in our designed reference
prompt. These candidate prompts are refined iteratively, while a scorer LLM
evaluates their effectiveness using the multi-dimensional metrics designed in
the objective prompts evaluator-a novel contribution in this work that provides
a holistic evaluation of prompt quality and task performance. This feedback
loop facilitates continuous refinement, optimizing both prompt quality and
task-specific outcomes. We validate Transfer-Prompting through extensive
experiments across 25 LLMs, including 7 foundational models and 18 specialized
models, evaluated on 9 diverse datasets. The results demonstrate that
Transfer-Prompting significantly improves task-specific performance,
highlighting its potential for enhancing cross-task adaptation in LLMs. The
code is available at https://github.com/llm172/Transfer-Prompting.
