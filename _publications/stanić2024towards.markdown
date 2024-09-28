---
layout: publication
title: Towards Truly Zero-shot Compositional Visual Reasoning with LLMs as Programmers
authors: Stanić Aleksandar, Caelles Sergi, Tschannen Michael
conference: "Arxiv"
year: 2024
bibkey: stanić2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.01974"}
tags: ['ARXIV', 'Applications']
---
Visual reasoning is dominated by end-to-end neural networks scaled to billions of model parameters and training examples. However even the largest models struggle with compositional reasoning generalization fine-grained spatial and temporal reasoning and counting. Visual reasoning with large language models (LLMs) as controllers can in principle address these limitations by decomposing the task and solving subtasks by orchestrating a set of (visual) tools. Recently these models achieved great performance on tasks such as compositional visual question answering visual grounding and video temporal reasoning. Nevertheless in their current form these models heavily rely on human engineering of in-context examples in the prompt which are often dataset- and task-specific and require significant labor by highly skilled programmers. In this work we present a framework that mitigates these issues by introducing spatially and temporally abstract routines and by leveraging a small number of labeled examples to automatically generate in-context examples thereby avoiding human-created in-context examples. On a number of visual reasoning tasks we show that our framework leads to consistent gains in performance makes LLMs as controllers setup more robust and removes the need for human engineering of in-context examples.
