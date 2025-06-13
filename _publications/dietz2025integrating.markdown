---
layout: publication
title: 'IGC: Integrating A Gated Calculator Into An LLM To Solve Arithmetic Tasks Reliably And Efficiently'
authors: Florian Dietz, Dietrich Klakow
conference: "Arxiv"
year: 2025
bibkey: dietz2025integrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00684"}
tags: ['Training Techniques', 'Tools']
---
Solving arithmetic tasks is a simple and fundamental skill, yet modern Large
Language Models (LLMs) have great difficulty with them. We introduce the
Integrated Gated Calculator (IGC), a module that enables LLMs to perform
arithmetic by emulating a calculator on the GPU. We finetune a Llama model with
our module and test it on the BigBench Arithmetic benchmark, where it beats the
State of the Art, outperforming all models on the benchmark, including models
almost two orders of magnitude larger. Our approach takes only a single
iteration to run and requires no external tools. It performs arithmetic
operations entirely inside the LLM without the need to produce intermediate
tokens. It is computationally efficient, interpretable, and avoids side-effects
on tasks that do not require arithmetic operations. It reliably achieves 98%
to 99% accuracy across multiple training runs and for all subtasks, including
the substantially harder subtask of multiplication, which was previously
unsolved.
