---
layout: publication
title: 'Shroom-indelab At Semeval-2024 Task 6: Zero- And Few-shot Llm-based Classification For Hallucination Detection'
authors: Bradley P. Allen, Fina Polat, Paul Groth
conference: "Arxiv"
year: 2024
bibkey: allen2024shroom
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.03732"}
tags: ['Few-Shot', 'Prompting', 'In-Context Learning']
---
We describe the University of Amsterdam Intelligent Data Engineering Lab
team's entry for the SemEval-2024 Task 6 competition. The SHROOM-INDElab system
builds on previous work on using prompt programming and in-context learning
with large language models (LLMs) to build classifiers for hallucination
detection, and extends that work through the incorporation of context-specific
definition of task, role, and target concept, and automated generation of
examples for use in a few-shot prompting approach. The resulting system
achieved fourth-best and sixth-best performance in the model-agnostic track and
model-aware tracks for Task 6, respectively, and evaluation using the
validation sets showed that the system's classification decisions were
consistent with those of the crowd-sourced human labellers. We further found
that a zero-shot approach provided better accuracy than a few-shot approach
using automatically generated examples. Code for the system described in this
paper is available on Github.
