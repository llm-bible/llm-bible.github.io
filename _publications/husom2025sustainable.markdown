---
layout: publication
title: 'Sustainable LLM Inference For Edge AI: Evaluating Quantized Llms For Energy Efficiency, Output Accuracy, And Inference Latency'
authors: Erik Johannes Husom, Arda Goknil, Merve Astekin, Lwin Khin Shar, Andre Kåsen, Sagar Sen, Benedikt Andreas Mithassel, Ahmet Soylu
conference: "Arxiv"
year: 2025
bibkey: husom2025sustainable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03360"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Quantization']
---
Deploying Large Language Models (LLMs) on edge devices presents significant
challenges due to computational constraints, memory limitations, inference
speed, and energy consumption. Model quantization has emerged as a key
technique to enable efficient LLM inference by reducing model size and
computational overhead. In this study, we conduct a comprehensive analysis of
28 quantized LLMs from the Ollama library, which applies by default
Post-Training Quantization (PTQ) and weight-only quantization techniques,
deployed on an edge device (Raspberry Pi 4 with 4GB RAM). We evaluate energy
efficiency, inference performance, and output accuracy across multiple
quantization levels and task types. Models are benchmarked on five standardized
datasets (CommonsenseQA, BIG-Bench Hard, TruthfulQA, GSM8K, and HumanEval), and
we employ a high-resolution, hardware-based energy measurement tool to capture
real-world power consumption. Our findings reveal the trade-offs between energy
efficiency, inference speed, and accuracy in different quantization settings,
highlighting configurations that optimize LLM deployment for
resource-constrained environments. By integrating hardware-level energy
profiling with LLM benchmarking, this study provides actionable insights for
sustainable AI, bridging a critical gap in existing research on energy-aware
LLM deployment.
