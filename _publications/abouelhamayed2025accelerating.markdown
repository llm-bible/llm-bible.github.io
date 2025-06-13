---
layout: publication
title: 'Sparamx: Accelerating Compressed Llms Token Generation On Amx-powered Cpus'
authors: Ahmed F. Abouelhamayed, Jordan Dotzel, Yash Akhauri, Chi-chih Chang, Sameh Gobriel, J. Pablo Muñoz, Vui Seng Chua, Nilesh Jain, Mohamed S. Abdelfattah
conference: "Arxiv"
year: 2025
bibkey: abouelhamayed2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12444"}
  - {name: "Code", url: "https://github.com/IntelLabs/Hardware-Aware-Automated-Machine-Learning/tree/main/SparAMX"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Large language models have high compute, latency, and memory requirements.
While specialized accelerators such as GPUs and TPUs typically run these
workloads, CPUs are more widely available and consume less energy. Accelerating
LLMs with CPUs enables broader AI access at a lower cost and power consumption.
This acceleration potential for CPUs is especially relevant during the
memory-bound decoding stage of LLM inference, which processes one token at a
time and is becoming increasingly utilized with reasoning models. We utilize
Advanced Matrix Extensions (AMX) support on the latest Intel CPUs together with
unstructured sparsity to achieve a \\(1.42 \times\\) reduction in end-to-end
latency compared to the current PyTorch implementation by applying our
technique in linear layers. We provide a set of open-source customized sparse
kernels that can speed up any PyTorch model by automatically replacing all
linear layers with our custom sparse implementation. Furthermore, we
demonstrate for the first time the use of unstructured sparsity in the
attention computation achieving a \\(1.14 \times\\) speedup over the current
systems without compromising accuracy. Code:
https://github.com/IntelLabs/Hardware-Aware-Automated-Machine-Learning/tree/main/SparAMX
