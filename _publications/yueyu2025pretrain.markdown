---
layout: publication
title: 'ARWKV: Pretrain Is Not What We Need, An Rnn-attention-based Language Model Born From Transformer'
authors: Lin Yueyu, Li Zhiyuan, Peter Yue, Liu Xiao
conference: "Arxiv"
year: 2025
bibkey: yueyu2025pretrain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15570"}
  - {name: "Code", url: "https://github.com/yynil/RWKVInside}{https://github.com/yynil/RWKVInside},"}
  - {name: "Code", url: "https://huggingface.co/RWKV-Red-Team/ARWKV-7B-Preview-0.1}{https://huggingface.co/RWKV-Red-Team/ARWKV-7B-Preview-0.1"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Distillation']
---
As is known, hybrid quadratic and subquadratic attention models in multi-head
architectures have surpassed both Transformer and Linear RNN models , with
these works primarily focusing on reducing KV complexity and improving
efficiency. For further research on expressiveness, we introduce our series of
models distilled from Qwen 2.5, based on pure native RWKV-7 attention, which
aims to make RNN more expressive and demonstrates state tracking ability beyond
transformers. We work with QRWK 32B based on RWKV-6 architecture, another
approach that reduces the entire knowledge processing time to just 8 hours
using 16 AMD MI300X GPUs while maintaining Qwen 2.5's performance. In fact, the
distillation process can utilize any LLM, not just Qwen, and enables knowledge
transfer from larger LLMs to smaller ones with more fewer tokens. We will
explain the detailed process and share our insights on building more powerful
foundation models. Please note that this is an ongoing work that will be
updated continuously. The model checkpoints and source code are available at
\href\{https://github.com/yynil/RWKVInside\}\{https://github.com/yynil/RWKVInside\},
\href\{https://huggingface.co/RWKV-Red-Team/ARWKV-7B-Preview-0.1\}\{https://huggingface.co/RWKV-Red-Team/ARWKV-7B-Preview-0.1\}.
