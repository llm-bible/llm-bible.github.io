---
layout: publication
title: 'Pay Attention To Real World Perturbations! Natural Robustness Evaluation In Machine Reading Comprehension'
authors: Yulong Wu, Viktor Schlegel, Riza Batista-navarro
conference: "Arxiv"
year: 2025
bibkey: wu2025pay
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.16523'}
tags: ['Attention Mechanism', 'RAG', 'Security', 'Model Architecture', 'Tools', 'Training Techniques', 'Reinforcement Learning']
---
As neural language models achieve human-comparable performance on Machine
Reading Comprehension (MRC) and see widespread adoption, ensuring their
robustness in real-world scenarios has become increasingly important. Current
robustness evaluation research, though, primarily develops synthetic
perturbation methods, leaving unclear how well they reflect real life
scenarios. Considering this, we present a framework to automatically examine
MRC models on naturally occurring textual perturbations, by replacing paragraph
in MRC benchmarks with their counterparts based on available Wikipedia edit
history. Such perturbation type is natural as its design does not stem from an
arteficial generative process, inherently distinct from the previously
investigated synthetic approaches. In a large-scale study encompassing SQUAD
datasets and various model architectures we observe that natural perturbations
result in performance degradation in pre-trained encoder language models. More
worryingly, these state-of-the-art Flan-T5 and Large Language Models (LLMs)
inherit these errors. Further experiments demonstrate that our findings
generalise to natural perturbations found in other more challenging MRC
benchmarks. In an effort to mitigate these errors, we show that it is possible
to improve the robustness to natural perturbations by training on naturally or
synthetically perturbed examples, though a noticeable gap still remains
compared to performance on unperturbed data.
