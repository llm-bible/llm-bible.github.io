---
layout: publication
title: Mammothmoda&#58; Multi-modal Large Language Model
authors: She Qi, Pan Junwen, Wan Xin, Zhang Rui, Lu Dawei, Huang Kai
conference: "Arxiv"
year: 2024
bibkey: she2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18193"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
In this report we introduce MammothModa yet another multi-modal large language model (MLLM) designed to achieve state-of-the-art performance starting from an elementary baseline. We focus on three key design insights (i) Integrating Visual Capabilities while Maintaining Complex Language Understanding In addition to the vision encoder we incorporated the Visual Attention Experts into the LLM to enhance its visual capabilities. (ii) Extending Context Window for High-Resolution and Long-Duration Visual Feature We explore the Visual Merger Module to effectively reduce the token number of high-resolution images and incorporated frame position ids to avoid position interpolation. (iii) High-Quality Bilingual Datasets We meticulously curated and filtered a high-quality bilingual multimodal dataset to reduce visual hallucinations. With above recipe we build MammothModa that consistently outperforms the state-of-the-art models e.g. LLaVA-series across main real-world visual language benchmarks without bells and whistles.
