---
layout: publication
title: 'Memory Is All You Need: An Overview Of Compute-in-memory Architectures For Accelerating Large Language Model Inference'
authors: Christopher Wolters, Xiaoxuan Yang, Ulf Schlichtmann, Toyotaro Suzumura
conference: "Arxiv"
year: 2024
bibkey: wolters2024memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08413"}
tags: ['Transformer', 'Efficiency and Optimization', 'Survey Paper', 'Model Architecture', 'Pretraining Methods']
---
Large language models (LLMs) have recently transformed natural language
processing, enabling machines to generate human-like text and engage in
meaningful conversations. This development necessitates speed, efficiency, and
accessibility in LLM inference as the computational and memory requirements of
these systems grow exponentially. Meanwhile, advancements in computing and
memory capabilities are lagging behind, exacerbated by the discontinuation of
Moore's law. With LLMs exceeding the capacity of single GPUs, they require
complex, expert-level configurations for parallel processing. Memory accesses
become significantly more expensive than computation, posing a challenge for
efficient scaling, known as the memory wall. Here, compute-in-memory (CIM)
technologies offer a promising solution for accelerating AI inference by
directly performing analog computations in memory, potentially reducing latency
and power consumption. By closely integrating memory and compute elements, CIM
eliminates the von Neumann bottleneck, reducing data movement and improving
energy efficiency. This survey paper provides an overview and analysis of
transformer-based models, reviewing various CIM architectures and exploring how
they can address the imminent challenges of modern AI computing systems. We
discuss transformer-related operators and their hardware acceleration schemes
and highlight challenges, trends, and insights in corresponding CIM designs.
