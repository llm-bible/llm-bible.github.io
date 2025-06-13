---
layout: publication
title: 'MELO: Enhancing Model Editing With Neuron-indexed Dynamic Lora'
authors: Lang Yu, Qin Chen, Jie Zhou, Liang He
conference: "Arxiv"
year: 2023
bibkey: yu2023enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.11795'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Efficiency and Optimization', 'Applications']
---
Large language models (LLMs) have shown great success in various Natural
Language Processing (NLP) tasks, whist they still need updates after deployment
to fix errors or keep pace with the changing knowledge in the world.
Researchers formulate such problem as Model Editing and have developed various
editors focusing on different axes of editing properties. However, current
editors can hardly support all properties and rely on heavy computational
resources. In this paper, we propose a plug-in Model Editing method based on
neuron-indexed dynamic LoRA (MELO), which alters the behavior of language
models by dynamically activating certain LoRA blocks according to the index
built in an inner vector database. Our method satisfies various editing
properties with high efficiency and can be easily integrated into multiple LLM
backbones. Experimental results show that our proposed MELO achieves
state-of-the-art editing performance on three sequential editing tasks
(document classification, question answering and hallucination correction),
while requires the least trainable parameters and computational cost.
