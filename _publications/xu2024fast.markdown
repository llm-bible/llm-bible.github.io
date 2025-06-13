---
layout: publication
title: 'Fast On-device LLM Inference With Npus'
authors: Daliang Xu, Hao Zhang, Liming Yang, Ruiqi Liu, Gang Huang, Mengwei Xu, Xuanzhe Liu
conference: "Arxiv"
year: 2024
bibkey: xu2024fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05858"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Transformer', 'Prompting']
---
On-device inference for Large Language Models (LLMs), driven by increasing
privacy concerns and advancements of mobile-sized models, has gained
significant interest. However, even mobile-sized LLMs (e.g., Gemma-2B)
encounter unacceptably high inference latency, often bottlenecked by the
prefill stage in tasks like screen UI understanding.
  We present llm.npu, the first LLM inference system utilizing on-device Neural
Processing Unit (NPU) offloading to reduce prefill latency. llm.npu enhances
NPU offloading efficiency by re-constructing the prompt and model in three
levels: (1) At prompt level, it divides variable-length prompts into multiple
fixed-sized chunks while maintaining data dependencies; (2) At tensor level, it
identifies and extracts significant outliers to run on the CPU/GPU in parallel
with minimal overhead; (3) At block level, it schedules Transformer blocks in
an out-of-order manner to the CPU/GPU and NPU based on their hardware affinity
and sensitivity to accuracy. Compared to competitive baselines, llm.npu
achieves 22.4x faster prefill speed and 30.7\\(\times\\) energy savings on average,
and up to 32.8x speedup in an end-to-end real-world application. For the first
time, llm.npu achieves more than 1,000 tokens/sec prefilling for a
billion-sized model.
