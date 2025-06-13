---
layout: publication
title: 'Can Large Language Models Predict Parallel Code Performance?'
authors: Gregory Bolet, Giorgis Georgakoudis, Harshitha Menon, Konstantinos Parasyris, Niranjan Hasabnis, Hayden Estes, Kirk W. Cameron, Gal Oren
conference: "Arxiv"
year: 2025
bibkey: bolet2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03988"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Few-Shot', 'Prompting']
---
Accurate determination of the performance of parallel GPU code typically
requires execution-time profiling on target hardware -- an increasingly
prohibitive step due to limited access to high-end GPUs. This paper explores
whether Large Language Models (LLMs) can offer an alternative approach for GPU
performance prediction without relying on hardware. We frame the problem as a
roofline classification task: given the source code of a GPU kernel and the
hardware specifications of a target GPU, can an LLM predict whether the GPU
kernel is compute-bound or bandwidth-bound?
  For this study, we build a balanced dataset of 340 GPU kernels, obtained from
HeCBench benchmark and written in CUDA and OpenMP, along with their
ground-truth labels obtained via empirical GPU profiling. We evaluate LLMs
across four scenarios: (1) with access to profiling data of the kernel source,
(2) zero-shot with source code only, (3) few-shot with code and label pairs,
and (4) fine-tuned on a small custom dataset.
  Our results show that state-of-the-art LLMs have a strong understanding of
the Roofline model, achieving 100% classification accuracy when provided with
explicit profiling data. We also find that reasoning-capable LLMs significantly
outperform standard LLMs in zero- and few-shot settings, achieving up to 64%
accuracy on GPU source codes, without profiling information. Lastly, we find
that LLM fine-tuning will require much more data than what we currently have
available.
  This work is among the first to use LLMs for source-level roofline
performance prediction via classification, and illustrates their potential to
guide optimization efforts when runtime profiling is infeasible. Our findings
suggest that with better datasets and prompt strategies, LLMs could become
practical tools for HPC performance analysis and performance portability.
