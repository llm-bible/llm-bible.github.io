---
layout: publication
title: 'Monocoder: Domain-specific Code Language Model For HPC Codes And Tasks'
authors: Tal Kadosh, Niranjan Hasabnis, Vy A. Vo, Nadav Schneider, Neva Krien, Mihai Capota, Abdul Wasay, Nesreen Ahmed, Ted Willke, Guy Tamir, Yuval Pinter, Timothy Mattson, Gal Oren
conference: "Arxiv"
year: 2023
bibkey: kadosh2023domain
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.13322'}
tags: ['Reinforcement Learning', 'Applications', 'Training Techniques']
---
With easier access to powerful compute resources, there is a growing trend in
AI for software development to develop large language models (LLMs) to address
a variety of programming tasks. Even LLMs applied to tasks from the
high-performance computing (HPC) domain are huge in size and demand expensive
compute resources for training. This is partly because LLMs for HPC tasks are
obtained by finetuning existing LLMs that support several natural and/or
programming languages. We found this design choice confusing - why do we need
LLMs trained on natural languages and programming languages unrelated to HPC
for HPC-specific tasks? In this line of work, we aim to question choices made
by existing LLMs by developing smaller language models (LMs) for specific
domains - we call them domain-specific LMs. Specifically, we start with HPC as
a domain and build an HPC-specific LM, named MonoCoder, which is orders of
magnitude smaller than existing LMs but delivers better performance on non-HPC
and HPC codes. Specifically, we pre-trained MonoCoder on an HPC-specific
dataset (named HPCorpus) of C and C++ programs mined from GitHub. We evaluated
the performance of MonoCoder against state-of-the-art multi-lingual LLMs.
Results demonstrate that MonoCoder, although much smaller than existing LMs,
outperforms other LLMs on normalized-perplexity tests (in relation to model
size) while also delivering competing CodeBLEU scores for high-performance and
parallel code generations. In other words, results suggest that MonoCoder
understands HPC code better than state-of-the-art LLMs.
