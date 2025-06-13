---
layout: publication
title: 'Chameleonllm: Batch-aware Dynamic Low-rank Adaptation Via Inference-time Clusters'
authors: Kamer Ali Yuksel, Hassan Sawaf
conference: "Arxiv"
year: 2025
bibkey: yuksel2025batch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04315"}
  - {name: "Code", url: "https://anonymous.4open.science/r/ChamaleonLLM/"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Recent advances in large language models (LLMs) have shown remarkable
performance across diverse tasks. However, these models are typically deployed
with fixed weights, which limits their ability to adapt dynamically to the
variability inherent in real-world data during inference. This paper introduces
ChameleonLLM, a novel framework that enables inference-time adaptation of LLMs
by leveraging batch-aware clustering and on-the-fly generation of low-rank
updates. Unlike traditional fine-tuning approaches such as Low-Rank Adaptation
(LoRA) or methods that rely on a fixed set of pre-learned uniforms (changeable
masks), our method dynamically generates adaptive modifications to the decoder
weights based on the aggregated statistics of clustered batches. By
intelligently grouping similar inputs and computing context-aware low-rank
updates via a hyper-network, ChameleonLLM achieves significant performance
gains, outperforming conventional LoRA methods while eliminating the overhead
of maintaining multiple expert models. Our experiments highlight the potential
of our approach to serve as a versatile and highly adaptive solution for
language model inference. ChameleonLLM is open-sourced to ensure the
reproducibility of our experiments:
https://anonymous.4open.science/r/ChamaleonLLM/
