---
layout: publication
title: 'Efficiently Integrate Large Language Models With Visual Perception: A Survey From The Training Paradigm Perspective'
authors: Xiaorui Ma, Haoran Xie, S. Joe Qin
conference: "Arxiv"
year: 2025
bibkey: ma2025efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01524"}
tags: ['Arxiv', 'Training Techniques', 'Multimodal Models', 'Efficiency and Optimization', 'Model Architecture', 'Survey Paper', 'Pretraining Methods']
---
The integration of vision-language modalities has been a significant focus in
multimodal learning, traditionally relying on Vision-Language Pretrained
Models. However, with the advent of Large Language Models (LLMs), there has
been a notable shift towards incorporating LLMs with vision modalities.
Following this, the training paradigms for incorporating vision modalities into
LLMs have evolved. Initially, the approach was to integrate the modalities
through pretraining the modality integrator, named Single-stage Tuning. It has
since branched out into methods focusing on performance enhancement, denoted as
Two-stage Tuning, and those prioritizing parameter efficiency, referred to as
Direct Adaptation. However, existing surveys primarily address the latest
Vision Large Language Models (VLLMs) with Two-stage Tuning, leaving a gap in
understanding the evolution of training paradigms and their unique
parameter-efficient considerations. This paper categorizes and reviews 34 VLLMs
from top conferences, journals, and highly cited Arxiv papers, focusing on
parameter efficiency during adaptation from the training paradigm perspective.
We first introduce the architecture of LLMs and parameter-efficient learning
methods, followed by a discussion on vision encoders and a comprehensive
taxonomy of modality integrators. We then review three training paradigms and
their efficiency considerations, summarizing benchmarks in the VLLM field. To
gain deeper insights into their effectiveness in parameter efficiency, we
compare and discuss the experimental results of representative models, among
which the experiment of the Direct Adaptation paradigm is replicated. Providing
insights into recent developments and practical uses, this survey is a vital
guide for researchers and practitioners navigating the efficient integration of
vision modalities into LLMs.
