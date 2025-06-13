---
layout: publication
title: 'Sc-lora: Balancing Efficient Fine-tuning And Knowledge Preservation Via Subspace-constrained Lora'
authors: Minrui Luo, Fuhang Kuang, Yu Wang, Zirui Liu, Tianxing He
conference: "Arxiv"
year: 2025
bibkey: luo2025sc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23724"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Parameter-Efficient Fine-Tuning (PEFT) methods, particularly Low-Rank Adaptation (LoRA), are indispensable for efficiently customizing Large Language Models (LLMs). However, vanilla LoRA suffers from slow convergence speed and knowledge forgetting problems. Recent studies have leveraged the power of designed LoRA initialization, to enhance the fine-tuning efficiency, or to preserve knowledge in the pre-trained LLM. However, none of these works can address the two cases at the same time. To this end, we introduce Subspace-Constrained LoRA (SC-LoRA), a novel LoRA initialization framework engineered to navigate the trade-off between efficient fine-tuning and knowledge preservation. We achieve this by constraining the output of trainable LoRA adapters in a low-rank subspace, where the context information of fine-tuning data is most preserved while the context information of preserved knowledge is least retained, in a balanced way. Such constraint enables the trainable weights to primarily focus on the main features of fine-tuning data while avoiding damaging the preserved knowledge features. We provide theoretical analysis on our method, and conduct extensive experiments including safety preservation and world knowledge preservation, on various downstream tasks. In our experiments, SC-LoRA succeeds in delivering superior fine-tuning performance while markedly diminishing knowledge forgetting, surpassing contemporary LoRA initialization methods.
