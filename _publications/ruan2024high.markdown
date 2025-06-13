---
layout: publication
title: 'Webllm: A High-performance In-browser LLM Inference Engine'
authors: Charlie F. Ruan, Yucheng Qin, Xun Zhou, Ruihang Lai, Hongyi Jin, Yixin Dong, Bohan Hou, Meng-shiun Yu, Yiyan Zhai, Sudeep Agarwal, Hangrui Cao, Siyuan Feng, Tianqi Chen
conference: "Arxiv"
year: 2024
bibkey: ruan2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15803"}
  - {name: "Code", url: "https://github.com/mlc-ai/web-llm"}
tags: ['Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Has Code']
---
Advancements in large language models (LLMs) have unlocked remarkable
capabilities. While deploying these models typically requires server-grade GPUs
and cloud-based inference, the recent emergence of smaller open-source models
and increasingly powerful consumer devices have made on-device deployment
practical. The web browser as a platform for on-device deployment is
universally accessible, provides a natural agentic environment, and
conveniently abstracts out the different backends from diverse device vendors.
To address this opportunity, we introduce WebLLM, an open-source JavaScript
framework that enables high-performance LLM inference entirely within web
browsers. WebLLM provides an OpenAI-style API for seamless integration into web
applications, and leverages WebGPU for efficient local GPU acceleration and
WebAssembly for performant CPU computation. With machine learning compilers
MLC-LLM and Apache TVM, WebLLM leverages optimized WebGPU kernels, overcoming
the absence of performant WebGPU kernel libraries. Evaluations show that WebLLM
can retain up to 80% native performance on the same device, with room to
further close the gap. WebLLM paves the way for universally accessible,
privacy-preserving, personalized, and locally powered LLM applications in web
browsers. The code is available at: https://github.com/mlc-ai/web-llm.
