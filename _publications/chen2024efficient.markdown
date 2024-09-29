---
layout: publication
title: Efficient and Economic Large Language Model Inference with Attention Offloading
authors: Chen Shaoyuan, Lin Yutong, Zhang Mingxing, Wu Yongwei
conference: "Arxiv"
year: 2024
bibkey: chen2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.01814"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Transformer-based large language models (LLMs) exhibit impressive performance in generative tasks but introduce significant challenges in real-world serving due to inefficient use of the expensive computation-optimized accelerators. This mismatch arises from the autoregressive nature of LLMs where the generation phase comprises operators with varying resource demands. Specifically the attention operator is memory-intensive exhibiting a memory access pattern that clashes with the strengths of modern accelerators especially as context length increases. To enhance the efficiency and cost-effectiveness of LLM serving we introduce the concept of attention offloading. This approach leverages a collection of cheap memory-optimized devices for the attention operator while still utilizing high-end accelerators for other parts of the model. This heterogeneous setup ensures that each component is tailored to its specific workload maximizing overall performance and cost efficiency. Our comprehensive analysis and experiments confirm the viability of splitting the attention computation over multiple devices. Also the communication bandwidth required between heterogeneous devices proves to be manageable with prevalent networking technologies. To further validate our theory we develop Lamina an LLM inference system that incorporates attention offloading. Experimental results indicate that Lamina can provide 1.48x-12.1x higher estimated throughput per dollar than homogeneous solutions.
