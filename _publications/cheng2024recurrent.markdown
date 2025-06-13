---
layout: publication
title: 'Recurrent Drafter For Fast Speculative Decoding In Large Language Models'
authors: Yunfei Cheng, Aonan Zhang, Xuanyu Zhang, Chong Wang, Yi Wang
conference: "Arxiv"
year: 2024
bibkey: cheng2024recurrent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09919"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'Distillation', 'Applications', 'Attention Mechanism']
---
We present Recurrent Drafter (ReDrafter), an advanced speculative decoding
approach that achieves state-of-the-art speedup for large language models
(LLMs) inference. The performance gains are driven by three key aspects: (1)
leveraging a recurrent neural network (RNN) as the draft model conditioning on
LLM's hidden states, (2) applying a dynamic tree attention algorithm over beam
search results to eliminate duplicated prefixes in candidate sequences, and (3)
training through knowledge distillation from the LLM. ReDrafter accelerates
Vicuna inference in MT-Bench by up to 2.8x with a PyTorch implementation on
Nvidia H100 GPUs. To demonstrate its practicality in real environments, we also
validated its effectiveness for on-device applications by implementing the
approach in MLX and benchmarking performance on Metal GPUs in Apple Silicon
chips, achieving up to 2.3x speedup.
