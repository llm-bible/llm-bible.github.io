---
layout: publication
title: 'ART: Automatic Multi-step Reasoning And Tool-use For Large Language Models'
authors: Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro
conference: "Arxiv"
year: 2023
bibkey: paranjape2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.09014"}
tags: ['Few-Shot', 'Tools', 'Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) can perform complex reasoning in few- and
zero-shot settings by generating intermediate chain of thought (CoT) reasoning
steps. Further, each reasoning step can rely on external tools to support
computation beyond the core LLM capabilities (e.g. search/running code). Prior
work on CoT prompting and tool use typically requires hand-crafting
task-specific demonstrations and carefully scripted interleaving of model
generations with tool use. We introduce Automatic Reasoning and Tool-use (ART),
a framework that uses frozen LLMs to automatically generate intermediate
reasoning steps as a program. Given a new task to solve, ART selects
demonstrations of multi-step reasoning and tool use from a task library. At
test time, ART seamlessly pauses generation whenever external tools are called,
and integrates their output before resuming generation. ART achieves a
substantial improvement over few-shot prompting and automatic CoT on unseen
tasks in the BigBench and MMLU benchmarks, and matches performance of
hand-crafted CoT prompts on a majority of these tasks. ART is also extensible,
and makes it easy for humans to improve performance by correcting errors in
task-specific programs or incorporating new tools, which we demonstrate by
drastically improving performance on select tasks with minimal human
intervention.
