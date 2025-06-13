---
layout: publication
title: 'JORA: JAX Tensor-parallel Lora Library For Retrieval Augmented Fine-tuning'
authors: Anique Tahir, Lu Cheng, Huan Liu
conference: "Arxiv"
year: 2024
bibkey: tahir2024jax
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11366"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Large-Scale Training', 'Fine-Tuning', 'Prompting', 'Applications']
---
The scaling of Large Language Models (LLMs) for retrieval-based tasks,
particularly in Retrieval Augmented Generation (RAG), faces significant memory
constraints, especially when fine-tuning extensive prompt sequences. Current
open-source libraries support full-model inference and fine-tuning across
multiple GPUs but fall short of accommodating the efficient parameter
distribution required for retrieved context. Addressing this gap, we introduce
a novel framework for PEFT-compatible fine-tuning of Llama-2 models, leveraging
distributed training. Our framework uniquely utilizes JAX's just-in-time (JIT)
compilation and tensor-sharding for efficient resource management, thereby
enabling accelerated fine-tuning with reduced memory requirements. This
advancement significantly improves the scalability and feasibility of
fine-tuning LLMs for complex RAG applications, even on systems with limited GPU
resources. Our experiments show more than 12x improvement in runtime compared
to Hugging Face/DeepSpeed implementation with four GPUs while consuming less
than half the VRAM per GPU.
