---
layout: publication
title: 'Private Lora Fine-tuning Of Open-source Llms With Homomorphic Encryption'
authors: Jordan Frery, Roman Bredehoft, Jakub Klemsa, Arthur Meyre, Andrei Stoian
conference: "Arxiv"
year: 2025
bibkey: frery2025private
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07329"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Preserving data confidentiality during the fine-tuning of open-source Large Language Models (LLMs) is crucial for sensitive applications. This work introduces an interactive protocol adapting the Low-Rank Adaptation (LoRA) technique for private fine-tuning. Homomorphic Encryption (HE) protects the confidentiality of training data and gradients handled by remote worker nodes performing the bulk of computations involving the base model weights. The data owner orchestrates training, requiring minimal local computing power and memory, thus alleviating the need for expensive client-side GPUs. We demonstrate feasibility by fine-tuning a Llama-3.2-1B model, presenting convergence results using HE-compatible quantization and performance benchmarks for HE computations on GPU hardware. This approach enables applications such as confidential knowledge base question answering, private codebase fine-tuning for AI code assistants, AI agents for drafting emails based on a company's email archive, and adapting models to analyze sensitive legal or healthcare documents.
