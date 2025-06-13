---
layout: publication
title: 'Kv-compress: Paged Kv-cache Compression With Variable Compression Rates Per Attention Head'
authors: Isaac Rehg
conference: "Arxiv"
year: 2024
bibkey: rehg2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.00161"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
Context lengths of Large Language Models (LLMs) have exploded in recent
years, with 128k-token context becoming a standard and million-token context
becoming a reality. Efficiently supporting long-context inference remains
challenging as the memory that must be allocated in key-value (KV) cache for a
generation scales with its context length, limiting the number of long-context
requests that can be served concurrently under a given memory budget. KV cache
compression can mitigate this issue by removing under-utilized KVs from each
attention head's cache and reducing its memory footprint. Higher theoretical
compression rates can be achieved when the number of removed KVs varies across
attention heads, but application of such a strategy within existing inference
frameworks adds fragmentation and cannot realize the theoretical compression
rates in physical memory. We introduce KV-Compress, a novel compression method
that evicts contiguous KV blocks within a PagedAttention framework, reducing
the memory footprint of the KV cache proportionally to this theoretical
compression rate. Our method achieves state-of-the-art performance on LongBench
for both Mistral-7B-Instruct-v0.2 and Llama-3.1-8B-Instruct while lowering the
total number of compressed KVs by 4x compared with prior methods. Evaluations
on Llama-3.1-8B-Instruct and Llama-3.1-70B-Instruct-FP8 achieve compression
rates up to 8x with negligible impact on performance, and up to 64x while
retaining over 90% of full-cache performance for all but three of the suite's
subsets. We benchmark an integration of our method with vLLM that increases
total throughput by up to 5.18x by enabling larger decoding batches.
