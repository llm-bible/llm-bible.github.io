---
layout: publication
title: 'FGMP: Fine-grained Mixed-precision Weight And Activation Quantization For Hardware-accelerated LLM Inference'
authors: Coleman Hooper, Charbel Sakr, Ben Keller, Rangharajan Venkatesan, Kurt Keutzer, Sophia Shao, Brucek Khailany
conference: "Arxiv"
year: 2025
bibkey: hooper2025fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14152'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Reinforcement Learning']
---
Quantization is a powerful tool to improve large language model (LLM)
inference efficiency by utilizing more energy-efficient low-precision datapaths
and reducing memory footprint. However, accurately quantizing LLM weights and
activations to low precision is challenging without degrading model accuracy.
We propose fine-grained mixed precision (FGMP) quantization, a post-training
mixed-precision quantization hardware-software co-design methodology that
maintains accuracy while quantizing the majority of weights and activations to
reduced precision. Our work makes the following contributions: 1) We develop a
policy that uses the perturbation in each value, weighted by the Fisher
information, to select which weight and activation blocks to keep in higher
precision. This approach preserves accuracy by identifying which weight and
activation blocks need to be retained in higher precision to minimize the
perturbation in the model loss. 2) We also propose a sensitivity-weighted
clipping approach for fine-grained quantization which helps retain accuracy for
blocks that are quantized to low precision. 3) We then propose hardware
augmentations to leverage the efficiency benefits of FGMP quantization. Our
hardware implementation encompasses i) datapath support for FGMP at block
granularity, and ii) a mixed-precision activation quantization unit to assign
activation blocks to high or low precision on the fly with minimal runtime and
energy overhead. Our design, prototyped using NVFP4 (an FP4 format with
microscaling) as the low-precision datatype and FP8 as the high-precision
datatype, facilitates efficient FGMP quantization, attaining <1% perplexity
degradation on Wikitext-103 for the Llama-2-7B model relative to an all-FP8
baseline design while consuming 14% less energy during inference and requiring
30% less weight memory.
