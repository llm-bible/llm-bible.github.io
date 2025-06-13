---
layout: publication
title: 'Accllm: Accelerating Long-context LLM Inference Via Algorithm-hardware Co-design'
authors: Yanbiao Liang, Huihong Shi, Haikuo Shao, Zhongfeng Wang
conference: "Arxiv"
year: 2025
bibkey: liang2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03745"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Pruning', 'Model Architecture', 'Attention Mechanism', 'Pretraining Methods', 'Quantization']
---
Recently, large language models (LLMs) have achieved huge success in the
natural language processing (NLP) field, driving a growing demand to extend
their deployment from the cloud to edge devices. However, deploying LLMs on
resource-constrained edge devices poses significant challenges, including (1)
intensive computations and huge model sizes, (2) great memory and bandwidth
demands introduced by the autoregressive generation process, and (3) limited
scalability for handling long sequences. To address these challenges, we
propose AccLLM, a comprehensive acceleration framework that enables efficient
and fast long-context LLM inference through algorithm and hardware co-design.
At the algorithmic level, we integrate (1) pruning, (2) \{\Lambda\}-shaped
attention, and (3) an innovative W2A8KV4 (2-bit weights, 8-bit activations, and
4-bit KV cache) quantization scheme, thus effectively reducing memory and
bandwidth requirements while facilitating LLMs' long-sequence generation. At
the hardware level, we design a dedicated FPGA-based accelerator with a
reconfigurable computing engine to effectively and flexibly accommodate diverse
operations arising from our compression algorithm, thereby fully translating
the algorithmic innovations into tangible hardware efficiency. We validate
AccLLM on the Xilinx Alveo U280 FPGA, demonstrating a 4.07x energy efficiency
and a 2.98x throughput compared to the state-of-the-art work FlightLLM.
