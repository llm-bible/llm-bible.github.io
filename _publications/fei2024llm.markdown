---
layout: publication
title: 'NITRO: LLM Inference On Intel Laptop Npus'
authors: Anthony Fei, Mohamed S. Abdelfattah
conference: "Arxiv"
year: 2024
bibkey: fei2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11053"}
  - {name: "Code", url: "https://github.com/abdelfattah-lab/nitro"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Has Code', 'Applications']
---
Large Language Models (LLMs) have become essential tools in natural language
processing, finding large usage in chatbots such as ChatGPT and Gemini, and are
a central area of research. A particular area of interest includes designing
hardware specialized for these AI applications, with one such example being the
neural processing unit (NPU). In 2023, Intel released the Intel Core Ultra
processor with codename Meteor Lake, featuring a CPU, GPU, and NPU
system-on-chip. However, official software support for the NPU through Intel's
OpenVINO framework is limited to static model inference. The dynamic nature of
autoregressive token generation in LLMs is therefore not supported out of the
box. To address this shortcoming, we present NITRO (NPU Inference for
Transformers Optimization), a Python-based framework built on top of OpenVINO
to support text and chat generation on NPUs. In this paper, we discuss in
detail the key modifications made to the transformer architecture to enable
inference, some performance benchmarks, and future steps towards improving the
package. The code repository for NITRO can be found here:
https://github.com/abdelfattah-lab/nitro.
