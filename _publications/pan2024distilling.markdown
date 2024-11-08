---
layout: publication
title: 'Distilling Large Language Models For Text-attributed Graph Learning'
authors: Pan Bo, Zhang Zheng, Zhang Yifei, Hu Yuntong, Zhao Liang
conference: "Arxiv"
year: 2024
bibkey: pan2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12022"}
tags: ['Applications', 'Few Shot', 'Tools', 'Training Techniques']
---
Text-Attributed Graphs (TAGs) are graphs of connected textual documents.
Graph models can efficiently learn TAGs, but their training heavily relies on
human-annotated labels, which are scarce or even unavailable in many
applications. Large language models (LLMs) have recently demonstrated
remarkable capabilities in few-shot and zero-shot TAG learning, but they suffer
from scalability, cost, and privacy issues. Therefore, in this work, we focus
on synergizing LLMs and graph models with their complementary strengths by
distilling the power of LLMs to a local graph model on TAG learning. To address
the inherent gaps between LLMs (generative models for texts) and graph models
(discriminative models for graphs), we propose first to let LLMs teach an
interpreter with rich textual rationale and then let a student model mimic the
interpreter's reasoning without LLMs' textual rationale. Extensive experiments
validate the efficacy of our proposed framework.
