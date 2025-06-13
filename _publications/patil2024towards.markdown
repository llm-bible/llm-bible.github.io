---
layout: publication
title: 'Towards Specification-driven Llm-based Generation Of Embedded Automotive Software'
authors: Minal Suresh Patil, Gustav Ung, Mattias Nyberg
conference: "Arxiv"
year: 2024
bibkey: patil2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.13269"}
tags: ['Training Techniques', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
The paper studies how code generation by LLMs can be combined with formal
verification to produce critical embedded software. The first contribution is a
general framework, spec2code, in which LLMs are combined with different types
of critics that produce feedback for iterative backprompting and fine-tuning.
The second contribution presents a first feasibility study, where a
minimalistic instantiation of spec2code, without iterative backprompting and
fine-tuning, is empirically evaluated using three industrial case studies from
the heavy vehicle manufacturer Scania. The goal is to automatically generate
industrial-quality code from specifications only. Different combinations of
formal ACSL specifications and natural language specifications are explored.
The results indicate that formally correct code can be generated even without
the application of iterative backprompting and fine-tuning.
