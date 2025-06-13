---
layout: publication
title: 'Qos-efficient Serving Of Multiple Mixture-of-expert Llms Using Partial Runtime Reconfiguration'
authors: Hamidreza Imani, Jiaxin Peng, Peiman Mohseni, Abdolah Amirany, Tarek El-ghazawi
conference: "Arxiv"
year: 2025
bibkey: imani2025qos
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.06481'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Merging', 'Pretraining Methods']
---
The deployment of mixture-of-experts (MoE) large language models (LLMs) presents significant challenges due to their high memory demands. These challenges become even more pronounced in multi-tenant environments, where shared resources must accommodate multiple models, limiting the effectiveness of conventional virtualization techniques. This paper addresses the problem of efficiently serving multiple fine-tuned MoE-LLMs on a single-GPU. We propose a serving system that employs \textit\{similarity-based expert consolidation\} to reduce the overall memory footprint by sharing similar experts across models. To ensure output quality, we introduce \textit\{runtime partial reconfiguration\}, dynamically replacing non-expert layers when processing requests from different models. As a result, our approach achieves a competitive output quality while maintaining throughput comparable to serving a single model while incurring a negligible increase in time-to-first-token (TTFT). Experiments on a server with a single NVIDIA A100 GPU (80GB) using Mixtral-8x7B models demonstrate an 85% average reduction in turnaround time compared to NVIDIA's multi-instance GPU (MIG). Furthermore, experiments on Google's Switch Transformer Base-8 model with up to four variants demonstrate the scalability and resilience of our approach in maintaining output quality compared to other model merging baselines, highlighting its effectiveness.
