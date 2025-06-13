---
layout: publication
title: 'Mg-verilog: Multi-grained Dataset Towards Enhanced Llm-assisted Verilog Generation'
authors: Yongan Zhang, Zhongzhi Yu, Yonggan Fu, Cheng Wan, Yingyan Celine Lin
conference: "Arxiv"
year: 2024
bibkey: zhang2024mg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.01910"}
tags: ['Fine-Tuning', 'Pre-Training', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have recently shown promise in streamlining
hardware design processes by encapsulating vast amounts of domain-specific
data. In addition, they allow users to interact with the design processes
through natural language instructions, thus making hardware design more
accessible to developers. However, effectively leveraging LLMs in hardware
design necessitates providing domain-specific data during inference (e.g.,
through in-context learning), fine-tuning, or pre-training. Unfortunately,
existing publicly available hardware datasets are often limited in size,
complexity, or detail, which hinders the effectiveness of LLMs in hardware
design tasks. To address this issue, we first propose a set of criteria for
creating high-quality hardware datasets that can effectively enhance
LLM-assisted hardware design. Based on these criteria, we propose a
Multi-Grained-Verilog (MG-Verilog) dataset, which encompasses descriptions at
various levels of detail and corresponding code samples. To benefit the broader
hardware design community, we have developed an open-source infrastructure that
facilitates easy access, integration, and extension of the dataset to meet
specific project needs. Furthermore, to fully exploit the potential of the
MG-Verilog dataset, which varies in complexity and detail, we introduce a
balanced fine-tuning scheme. This scheme serves as a unique use case to
leverage the diverse levels of detail provided by the dataset. Extensive
experiments demonstrate that the proposed dataset and fine-tuning scheme
consistently improve the performance of LLMs in hardware design tasks.
