---
layout: publication
title: 'Spotlight Your Instructions: Instruction-following With Dynamic Attention Steering'
authors: Praveen Venkateswaran, Danish Contractor
conference: "Arxiv"
year: 2025
bibkey: venkateswaran2025spotlight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12025"}
tags: ['Applications', 'Ethics and Bias', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Prompting']
---
In many real-world applications, users rely on natural language instructions to guide large language models (LLMs) across a wide range of tasks. These instructions are often complex, diverse, and subject to frequent change. However, LLMs do not always attend to these instructions reliably, and users lack simple mechanisms to emphasize their importance beyond modifying prompt wording or structure. To address this, we present an inference-time method that enables users to emphasize specific parts of their prompt by steering the model's attention toward them, aligning the model's perceived importance of different prompt tokens with user intent. Unlike prior approaches that are limited to static instructions, require significant offline profiling, or rely on fixed biases, we dynamically update the proportion of model attention given to the user-specified parts--ensuring improved instruction following without performance degradation. We demonstrate that our approach improves instruction following across a variety of tasks involving multiple instructions and generalizes across models of varying scales.
