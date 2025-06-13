---
layout: publication
title: 'Scope Is All You Need: Transforming Llms For HPC Code'
authors: Tal Kadosh, Niranjan Hasabnis, Vy A. Vo, Nadav Schneider, Neva Krien, Abdul Wasay, Nesreen Ahmed, Ted Willke, Guy Tamir, Yuval Pinter, Timothy Mattson, Gal Oren
conference: "Arxiv"
year: 2023
bibkey: kadosh2023scope
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.09440'}
tags: ['RAG', 'Training Techniques']
---
With easier access to powerful compute resources, there is a growing trend in
the field of AI for software development to develop larger and larger language
models (LLMs) to address a variety of programming tasks. Even LLMs applied to
tasks from the high-performance computing (HPC) domain are huge in size (e.g.,
billions of parameters) and demand expensive compute resources for training. We
found this design choice confusing - why do we need large LLMs trained on
natural languages and programming languages unrelated to HPC for HPC-specific
tasks? In this line of work, we aim to question design choices made by existing
LLMs by developing smaller LLMs for specific domains - we call them
domain-specific LLMs. Specifically, we start off with HPC as a domain and
propose a novel tokenizer named Tokompiler, designed specifically for
preprocessing code in HPC and compilation-centric tasks. Tokompiler leverages
knowledge of language primitives to generate language-oriented tokens,
providing a context-aware understanding of code structure while avoiding human
semantics attributed to code structures completely. We applied Tokompiler to
pre-train two state-of-the-art models, SPT-Code and Polycoder, for a Fortran
code corpus mined from GitHub. We evaluate the performance of these models
against the conventional LLMs. Results demonstrate that Tokompiler
significantly enhances code completion accuracy and semantic understanding
compared to traditional tokenizers in normalized-perplexity tests, down to ~1
perplexity score. This research opens avenues for further advancements in
domain-specific LLMs, catering to the unique demands of HPC and compilation
tasks.
