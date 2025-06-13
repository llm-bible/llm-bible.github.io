---
layout: publication
title: 'DOVE: A Large-scale Multi-dimensional Predictions Dataset Towards Meaningful LLM Evaluation'
authors: Eliya Habba, Ofir Arviv, Itay Itzhak, Yotam Perlitz, Elron Bandel, Leshem Choshen, Michal Shmueli-scheuer, Gabriel Stanovsky
conference: "Arxiv"
year: 2025
bibkey: habba2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01622"}
tags: ['Prompting', 'Few-Shot']
---
Recent work found that LLMs are sensitive to a wide range of arbitrary prompt dimensions, including the type of delimiters, answer enumerators, instruction wording, and more. This throws into question popular single-prompt evaluation practices. We present DOVE (Dataset Of Variation Evaluation) a large-scale dataset containing prompt perturbations of various evaluation benchmarks. In contrast to previous work, we examine LLM sensitivity from an holistic perspective, and assess the joint effects of perturbations along various dimensions, resulting in thousands of perturbations per instance. We evaluate several model families against DOVE, leading to several findings, including efficient methods for choosing well-performing prompts, observing that few-shot examples reduce sensitivity, and identifying instances which are inherently hard across all perturbations. DOVE consists of more than 250M prompt perturbations and model outputs, which we make publicly available to spur a community-wide effort toward meaningful, robust, and efficient evaluation.
  Browse the data, contribute, and more: https://slab-nlp.github.io/DOVE/
