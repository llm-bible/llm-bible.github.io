---
layout: publication
title: 'Splitfrozen: Split Learning With Device-side Model Frozen For Fine-tuning LLM On Heterogeneous Resource-constrained Devices'
authors: Jian Ma, Xinchen Lyu, Jun Jiang, Qimei Cui, Haipeng Yao, Xiaofeng Tao
conference: "Arxiv"
year: 2025
bibkey: ma2025split
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.18986'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Fine-Tuning', 'GPT', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) on private, on-device data can
empower tailored personalized AI agents. However, fine-tuning LLMs on
resource-constrained edge devices faces significant challenges, including
excessive computation overhead, device heterogeneity, and data imbalance. This
paper proposes SplitFrozen, a split learning framework that enables efficient
LLM fine-tuning by strategically freezing device-side model layers while
centralizing parameter-efficient fine-tuning on the server. Our framework
partitions LLMs into device-side frozen layers and server-side fine-tuning
layers, where heterogeneous resource-constrained devices execute only forward
propagation. To minimize server-side training costs, we integrate Low-Rank
Adaptation (LoRA) into the server-side layers. A pipeline parallelism strategy
further optimizes training efficiency by decoupling device-server computations
and leveraging decomposed backward propagation. Experiments on GPT-2 with the
MRPC, MNLI-matched, and SST-2 datasets demonstrate that SplitFrozen outperforms
FedLoRA and SplitLoRA by 69.4% model accuracy under extremely imbalanced data,
while reducing up to 86.8% device-side computations and 50.2% total training
time. Experiments also validate the scalability of SplitFrozen on content
generation task using Llama-3.2 model on GSM8K dataset.
