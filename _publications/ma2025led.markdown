---
layout: publication
title: 'Led-merging: Mitigating Safety-utility Conflicts In Model Merging With Location-election-disjoint'
authors: Qianli Ma, Dongrui Liu, Qian Chen, Linfeng Zhang, Jing Shao
conference: "Arxiv"
year: 2025
bibkey: ma2025led
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.16770"}
tags: ['Responsible AI', 'Training Techniques', 'Tools', 'Merging', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning pre-trained Large Language Models (LLMs) for specialized tasks
incurs substantial computational and data costs. While model merging offers a
training-free solution to integrate multiple task-specific models, existing
methods suffer from safety-utility conflicts where enhanced general
capabilities degrade safety safeguards. We identify two root causes:
\textbf\{neuron misidentification\} due to simplistic parameter magnitude-based
selection, and \textbf\{cross-task neuron interference\} during merging. To
address these challenges, we propose \textbf\{LED-Merging\}, a three-stage
framework that \textbf\{L\}ocates task-specific neurons via gradient-based
attribution, dynamically \textbf\{E\}lects critical neurons through multi-model
importance fusion, and \textbf\{D\}isjoints conflicting updates through parameter
isolation. Extensive experiments on Llama-3-8B, Mistral-7B, and Llama2-13B
demonstrate that LED-Merging reduces harmful response rates(*e.g.*, a
31.4% decrease on Llama-3-8B-Instruct on HarmBench) while preserving 95% of
utility performance(*e.g.*, 52.39% accuracy on GSM8K). LED-Merging
resolves safety-utility conflicts and provides a lightweight, training-free
paradigm for constructing reliable multi-task LLMs.
