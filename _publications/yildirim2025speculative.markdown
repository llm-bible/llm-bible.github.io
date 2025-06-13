---
layout: publication
title: 'Specmemo: Speculative Decoding Is In Your Pocket'
authors: Selin Yildirim, Deming Chen
conference: "Arxiv"
year: 2025
bibkey: yildirim2025speculative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01986'}
tags: ['Reinforcement Learning', 'Model Architecture', 'Applications', 'Tools']
---
Recent advancements in speculative decoding have demonstrated considerable speedup across a wide array of large language model (LLM) tasks. Speculative decoding inherently relies on sacrificing extra memory allocations to generate several candidate tokens, of which acceptance rate drives the speedup. However, deploying speculative decoding on memory-constrained devices, such as mobile GPUs, remains as a significant challenge in real-world scenarios. In this work, we present a device-aware inference engine named SpecMemo that can smartly control memory allocations at finer levels to enable multi-turn chatbots with speculative decoding on such limited memory devices. Our methodology stems from theoretically modeling memory footprint of speculative decoding to determine a lower bound on the required memory budget while retaining speedup. SpecMemo empirically acquires a careful balance between minimizing redundant memory allocations for rejected candidate tokens and maintaining competitive performance gains from speculation. Notably, with SpecMemo's memory management, we maintain 96% of overall throughput from speculative decoding on MT-Bench, with reduced generation-memory by 65% on single Nvidia Titan RTX. Given multiple constrained GPUs, we build on top of previous speculative decoding architectures to facilitate big-model inference by distributing Llama-2-70B-Chat model, on which we provide novel batched speculative decoding to increase usability of multiple small server GPUs. This novel framework demonstrates 2x speedup over distributed and batched vanilla decoding with the base model on eight AMD MI250 GPUs. Moreover, inference throughput increases remarkably 8x with batch size 10. Our work contributes to democratized LLM applications in resource-constrained environments, providing a pathway for faster and cheaper deployment of real-world LLM applications with robust performance.
