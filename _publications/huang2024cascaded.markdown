---
layout: publication
title: 'Align\(^2\)llava: Cascaded Human And Large Language Model Preference Alignment For Multi-modal Instruction Curation'
authors: Hongzhe Huang, Jiang Liu, Zhewen Yu, Li Cai, Dian Jiao, Wenqiao Zhang, Siliang Tang, Juncheng Li, Hao Jiang, Haoyuan Li, Yueting Zhuang
conference: "Arxiv"
year: 2024
bibkey: huang2024cascaded
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.18541'}
  - {name: "Code", url: 'https://github.com/DCDmllm/Align2LLaVA'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Recent advances in Multi-modal Large Language Models (MLLMs), such as
LLaVA-series models, are driven by massive machine-generated
instruction-following data tuning. Such automatic instruction collection
pipelines, however, inadvertently introduce significant variability in data
quality. This paper introduces a novel instruction curation algorithm, derived
from two unique perspectives, human and LLM preference alignment, to compress
this vast corpus of machine-generated multimodal instructions to a compact and
high-quality form: (i) For human preference alignment, we have collected a
machine-generated multimodal instruction dataset and established a
comprehensive set of both subjective and objective criteria to guide the data
quality assessment critically from human experts. By doing so, a reward model
was trained on the annotated dataset to internalize the nuanced human
understanding of instruction alignment. (ii) For LLM preference alignment,
given the instruction selected by the reward model, we propose leveraging the
inner LLM used in MLLM to align the writing style of visual instructions with
that of the inner LLM itself, resulting in LLM-aligned instruction improvement.
Extensive experiments demonstrate that we can maintain or even improve model
performance by compressing synthetic multimodal instructions by up to 90%.
Impressively, by aggressively reducing the training instructions from 158k to
14k (9\\(\times\\) smaller), our model consistently outperforms its full-size
dataset counterpart across various MLLM benchmarks. Our project is available at
https://github.com/DCDmllm/Align2LLaVA.
