---
layout: publication
title: 'Fine, I''ll Merge It Myself: A Multi-fidelity Framework For Automated Model Merging'
authors: Guinan Su, Jonas Geiping
conference: "Arxiv"
year: 2025
bibkey: su2025merge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04030'}
tags: ['Efficiency and Optimization', 'Tools', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Reinforcement Learning']
---
Reasoning capabilities represent a critical frontier for large language
models (LLMs), but developing them requires extensive proprietary datasets and
computational resources. One way to efficiently supplement capabilities with is
by model merging, which offers a promising alternative by combining multiple
models without retraining. However, current merging approaches rely on
manually-designed strategies for merging hyperparameters, limiting the
exploration of potential model combinations and requiring significant human
effort. We propose an Automated Model Merging Framework that enables
fine-grained exploration of merging strategies while reducing costs through
multi-fidelity approximations. We support both single and multi-objective
optimization and introduce two novel search spaces: layerwise fusion (LFS) and
depth-wise integration (DIS). Evaluating across a number of benchmarks, we find
that the search autonomously finds 1) Merges that further boost
single-objective performance, even on tasks the model has already been
finetuned on, and 2) Merges that optimize multi-objective frontiers across
tasks. Effective merges are found with limited compute, e.g. within less than
500 search steps.
