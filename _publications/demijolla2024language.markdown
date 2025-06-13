---
layout: publication
title: 'Language Hooks: A Modular Framework For Augmenting LLM Reasoning That Decouples Tool Usage From The Model And Its Prompt'
authors: Damien De Mijolla, Wen Yang, Philippa Duckett, Christopher Frye, Mark Worrall
conference: "Arxiv"
year: 2024
bibkey: demijolla2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05967"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Prompting and fine-tuning have emerged as two competing paradigms for
augmenting language models with new capabilities, such as the use of tools.
Prompting approaches are quick to set up but rely on providing explicit
demonstrations of each tool's usage in the model's prompt, thus coupling tool
use to the task at hand and limiting generalisation. Fine-tuning removes the
need for task-specific demonstrations of tool usage at runtime; however, this
ties new capabilities to a single model, thus making already-heavier setup
costs a recurring expense. In this paper, we introduce language hooks, a novel
framework for augmenting language models with new capabilities that is
decoupled both from the model's task-specific prompt and from the model itself.
The language hook algorithm interleaves text generation by the base model with
the execution of modular programs that trigger conditionally based on the
existing text and the available capabilities. Upon triggering, programs may
call external tools, auxiliary language models (e.g. using tool specific
prompts), and modify the existing context. We benchmark our method against
state-of-the-art baselines, find that it outperforms task-aware approaches, and
demonstrate its ability to generalise to novel tasks.
