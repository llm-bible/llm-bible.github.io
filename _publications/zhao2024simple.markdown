---
layout: publication
title: 'Prepacking: A Simple Method For Fast Prefilling And Increased Throughput In Large Language Models'
authors: Zhao Siyan, Israel Daniel, Broeck Guy Van Den, Grover Aditya
conference: "Arxiv"
year: 2024
bibkey: zhao2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09529"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Transformer']
---
During inference for transformer-based large language models (LLM) prefilling is the computation of the key-value (KV) cache for input tokens in the prompt prior to autoregressive generation. For longer input prompt lengths prefilling will incur a significant overhead on decoding time. In this work we highlight the following pitfall of prefilling for batches containing high-varying prompt lengths significant computation is wasted by the standard practice of padding sequences to the maximum length. As LLMs increasingly support longer context lengths potentially up to 10 million tokens variations in prompt lengths within a batch become more pronounced. To address this we propose Prepacking a simple yet effective method to optimize prefilling computation. To avoid redundant computation on pad tokens prepacking combines prompts of varying lengths into a sequence and packs multiple sequences into a compact batch using a bin-packing algorithm. It then modifies the attention mask and positional encoding to compute multiple prefilled KV-caches for multiple prompts within a single sequence. On standard curated dataset containing prompts with varying lengths we obtain a significant speed and memory efficiency improvements as compared to the default padding-based prefilling computation within Huggingface across a range of base model configurations and inference serving scenarios.
