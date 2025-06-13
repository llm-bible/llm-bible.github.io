---
layout: publication
title: 'Hdlcore: A Training-free Framework For Mitigating Hallucinations In Llm-generated HDL'
authors: Heng Ping, Shixuan Li, Peiyu Zhang, Anzhe Cheng, Shukai Duan, Nikos Kanakaris, Xiongye Xiao, Wei Yang, Shahin Nazarian, Andrei Irimia, Paul Bogdan
conference: "Arxiv"
year: 2025
bibkey: ping2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.16528'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Recent advances in large language models (LLMs) have demonstrated remarkable
capabilities in code generation tasks. However, when applied to hardware
description languages (HDL), these models exhibit significant limitations due
to data scarcity, resulting in hallucinations and incorrect code generation. To
address these challenges, we propose HDLCoRe, a training-free framework that
enhances LLMs' HDL generation capabilities through prompt engineering
techniques and retrieval-augmented generation (RAG). Our approach consists of
two main components: (1) an HDL-aware Chain-of-Thought (CoT) prompting
technique with self-verification that classifies tasks by complexity and type,
incorporates domain-specific knowledge, and guides LLMs through step-by-step
self-simulation for error correction; and (2) a two-stage heterogeneous RAG
system that addresses formatting inconsistencies through key component
extraction and efficiently retrieves relevant HDL examples through sequential
filtering and re-ranking. HDLCoRe eliminates the need for model fine-tuning
while substantially improving LLMs' HDL generation capabilities. Experimental
results demonstrate that our framework achieves superior performance on the
RTLLM2.0 benchmark, significantly reducing hallucinations and improving both
syntactic and functional correctness.
