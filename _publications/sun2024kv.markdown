---
layout: publication
title: 'Shadowkv: KV Cache In Shadows For High-throughput Long-context LLM Inference'
authors: Hanshi Sun, Li-wen Chang, Wenlei Bao, Size Zheng, Ningxin Zheng, Xin Liu, Harry Dong, Yuejie Chi, Beidi Chen
conference: "Arxiv"
year: 2024
bibkey: sun2024kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.21465"}
  - {name: "Code", url: "https://github.com/bytedance/ShadowKV"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
With the widespread deployment of long-context large language models (LLMs),
there has been a growing demand for efficient support of high-throughput
inference. However, as the key-value (KV) cache expands with the sequence
length, the increasing memory footprint and the need to access it for each
token generation both result in low throughput when serving long-context LLMs.
While various dynamic sparse attention methods have been proposed to speed up
inference while maintaining generation quality, they either fail to
sufficiently reduce GPU memory consumption or introduce significant decoding
latency by offloading the KV cache to the CPU. We present ShadowKV, a
high-throughput long-context LLM inference system that stores the low-rank key
cache and offloads the value cache to reduce the memory footprint for larger
batch sizes and longer sequences. To minimize decoding latency, ShadowKV
employs an accurate KV selection strategy that reconstructs minimal sparse KV
pairs on-the-fly. By evaluating ShadowKV on a broad range of benchmarks,
including RULER, LongBench, and Needle In A Haystack, and models like
Llama-3.1-8B, Llama-3-8B-1M, GLM-4-9B-1M, Yi-9B-200K, Phi-3-Mini-128K, and
Qwen2-7B-128K, we demonstrate that it can support up to 6\\(\times\\) larger batch
sizes and boost throughput by up to 3.04\\(\times\\) on an A100 GPU without
sacrificing accuracy, even surpassing the performance achievable with infinite
batch size under the assumption of infinite GPU memory. The code is available
at https://github.com/bytedance/ShadowKV.
