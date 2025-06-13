---
layout: publication
title: 'Optimising Hard Prompts With Few-shot Meta-prompting'
authors: Sayash Raaj Hiraou
conference: "Arxiv"
year: 2024
bibkey: hiraou2024optimising
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18920"}
tags: ['Prompting', 'Training Techniques', 'Few-Shot']
---
Prompting is a flexible and adaptable way of providing instructions to a
Large Language Model (LLM). Contextual prompts include context in the form of a
document or dialogue along with the natural language instructions to the LLM,
often constraining the LLM to restrict facts to that of the given context while
complying with the instructions. Masking the context, it acts as template for
prompts. In this paper, we present an iterative method to generate better
templates using an LLM from an existing set of prompt templates without
revealing the context to the LLM. Multiple methods of optimising prompts using
the LLM itself are explored to check the effect of few shot sampling methods on
iterative propagation while maintaining linguistic styles and syntax on
optimisation of prompt templates, yielding a 103.87% improvement using the best
performing method. Comparison of the results of multiple contextual tasks
demonstrate the ability of LLMs to maintain syntax while learning to replicate
linguistic styles. Additionally, the effect on the output with different
methods of prompt template generation is shown.
