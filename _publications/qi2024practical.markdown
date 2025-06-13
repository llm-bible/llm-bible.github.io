---
layout: publication
title: 'Practical Token Pruning For Foundation Models In Few-shot Conversational Virtual Assistant Systems'
authors: Haode Qi, Cheng Qian, Jian Ni, Pratyush Singh, Reza Fazeli, Gengyu Wang, Zhongzheng Shu, Eric Wayne, Juergen Bross
conference: "Arxiv"
year: 2024
bibkey: qi2024practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11799"}
tags: ['Transformer', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Few-Shot', 'Distillation']
---
In an enterprise Virtual Assistant (VA) system, intent classification is the
crucial component that determines how a user input is handled based on what the
user wants. The VA system is expected to be a cost-efficient SaaS service with
low training and inference time while achieving high accuracy even with a small
number of training samples. We pretrain a transformer-based sentence embedding
model with a contrastive learning objective and leverage the embedding of the
model as features when training intent classification models. Our approach
achieves the state-of-the-art results for few-shot scenarios and performs
better than other commercial solutions on popular intent classification
benchmarks. However, generating features via a transformer-based model
increases the inference time, especially for longer user inputs, due to the
quadratic runtime of the transformer's attention mechanism. On top of model
distillation, we introduce a practical multi-task adaptation approach that
configures dynamic token pruning without the need for task-specific training
for intent classification. We demonstrate that this approach improves the
inference speed of popular sentence transformer models without affecting model
performance.
