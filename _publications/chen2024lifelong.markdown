---
layout: publication
title: 'Lifelong Knowledge Editing For Vision Language Models With Low-rank Mixture-of-experts'
authors: Qizhou Chen, Chengyu Wang, Dakan Wang, Taolin Zhang, Wangyue Li, Xiaofeng He
conference: "Arxiv"
year: 2024
bibkey: chen2024lifelong
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.15432"}
tags: ['Applications', 'Merging', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Model editing aims to correct inaccurate knowledge, update outdated
information, and incorporate new data into Large Language Models (LLMs) without
the need for retraining. This task poses challenges in lifelong scenarios where
edits must be continuously applied for real-world applications. While some
editors demonstrate strong robustness for lifelong editing in pure LLMs, Vision
LLMs (VLLMs), which incorporate an additional vision modality, are not directly
adaptable to existing LLM editors. In this paper, we propose LiveEdit, a
LIfelong Vision language modEl Edit to bridge the gap between lifelong LLM
editing and VLLMs. We begin by training an editing expert generator to
independently produce low-rank experts for each editing instance, with the goal
of correcting the relevant responses of the VLLM. A hard filtering mechanism is
developed to utilize visual semantic knowledge, thereby coarsely eliminating
visually irrelevant experts for input queries during the inference stage of the
post-edited model. Finally, to integrate visually relevant experts, we
introduce a soft routing mechanism based on textual semantic relevance to
achieve multi-expert fusion. For evaluation, we establish a benchmark for
lifelong VLLM editing. Extensive experiments demonstrate that LiveEdit offers
significant advantages in lifelong VLLM editing scenarios. Further experiments
validate the rationality and effectiveness of each module design in LiveEdit.
