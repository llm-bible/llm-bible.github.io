---
layout: publication
title: JORA JAX Tensor45;parallel Lora Library For Retrieval Augmented Fine45;tuning
authors: Tahir Anique, Cheng Lu, Liu Huan
conference: "Arxiv"
year: 2024
bibkey: tahir2024jax
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11366"}
tags: ['Applications', 'Fine Tuning', 'Large Scale Training', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
The scaling of Large Language Models (LLMs) for retrieval45;based tasks particularly in Retrieval Augmented Generation (RAG) faces significant memory constraints especially when fine45;tuning extensive prompt sequences. Current open45;source libraries support full45;model inference and fine45;tuning across multiple GPUs but fall short of accommodating the efficient parameter distribution required for retrieved context. Addressing this gap we introduce a novel framework for PEFT45;compatible fine45;tuning of Llama45;2 models leveraging distributed training. Our framework uniquely utilizes JAXs just45;in45;time (JIT) compilation and tensor45;sharding for efficient resource management thereby enabling accelerated fine45;tuning with reduced memory requirements. This advancement significantly improves the scalability and feasibility of fine45;tuning LLMs for complex RAG applications even on systems with limited GPU resources. Our experiments show more than 12x improvement in runtime compared to Hugging Face/DeepSpeed implementation with four GPUs while consuming less than half the VRAM per GPU.
