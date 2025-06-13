---
layout: publication
title: 'Unlocking Structured Thinking In Language Models With Cognitive Prompting'
authors: Oliver Kramer, Jill Baumann
conference: "Arxiv"
year: 2024
bibkey: kramer2024unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02953"}
tags: ['Few-Shot', 'Prompting', 'Applications']
---
We propose cognitive prompting as a novel approach to guide problem-solving
in large language models (LLMs) through structured, human-like cognitive
operations, such as goal clarification, decomposition, filtering, abstraction,
and pattern recognition. By employing systematic, step-by-step reasoning,
cognitive prompting enables LLMs to tackle complex, multi-step tasks more
efficiently. We introduce three variants: a deterministic sequence of cognitive
operations, a self-adaptive variant in which the LLM dynamically selects the
sequence of cognitive operations, and a hybrid variant that uses generated
correct solutions as few-shot chain-of-thought prompts. Experiments with LLaMA,
Gemma~2, and Qwen models in each two sizes on the arithmetic reasoning
benchmark GSM8K demonstrate that cognitive prompting significantly improves
performance compared to standard question answering.
