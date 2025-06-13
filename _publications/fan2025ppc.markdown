---
layout: publication
title: 'PPC-GPT: Federated Task-specific Compression Of Large Language Models Via Pruning And Chain-of-thought Distillation'
authors: Tao Fan, Guoqiang Ma, Yuanfeng Song, Lixin Fan, Kai Chen, Qiang Yang
conference: "Arxiv"
year: 2025
bibkey: fan2025ppc
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.15857'}
tags: ['Language Modeling', 'RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Applications', 'Pruning']
---
Compressing Large Language Models (LLMs) into task-specific Small Language
Models (SLMs) encounters two significant challenges: safeguarding
domain-specific knowledge privacy and managing limited resources. To tackle
these challenges, we propose PPC-GPT, a innovative privacy-preserving federated
framework specifically designed for compressing LLMs into task-specific SLMs
via pruning and Chain-of-Thought (COT) distillation. PPC-GPT works on a
server-client federated architecture, where the client sends differentially
private (DP) perturbed task-specific data to the server's LLM. The LLM then
generates synthetic data along with their corresponding rationales. This
synthetic data is subsequently used for both LLM pruning and retraining
processes. Additionally, we harness COT knowledge distillation, leveraging the
synthetic data to further improve the retraining of structurally-pruned SLMs.
Our experimental results demonstrate the effectiveness of PPC-GPT across
various text generation tasks. By compressing LLMs into task-specific SLMs,
PPC-GPT not only achieves competitive performance but also prioritizes data
privacy protection.
