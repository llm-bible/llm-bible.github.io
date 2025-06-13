---
layout: publication
title: 'Distilqwen2.5: Industrial Practices Of Training Distilled Open Lightweight Language Models'
authors: Chengyu Wang, Junbing Yan, Yuanhao Yue, Jun Huang
conference: "Arxiv"
year: 2025
bibkey: wang2025industrial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15027"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Distillation', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Enhancing computational efficiency and reducing deployment costs for large
language models (LLMs) have become critical challenges in various
resource-constrained scenarios. In this work, we present DistilQwen2.5, a
family of distilled, lightweight LLMs derived from the public Qwen2.5 models.
These distilled models exhibit enhanced instruction-following capabilities
compared to the original models based on a series of distillation techniques
that incorporate knowledge from much larger LLMs. In our industrial practice,
we first leverage powerful proprietary LLMs with varying capacities as
multi-agent teachers to select, rewrite, and refine instruction-response pairs
that are more suitable for student LLMs to learn. After standard fine-tuning,
we further leverage a computationally efficient model fusion approach that
enables student models to progressively integrate fine-grained hidden knowledge
from their teachers. Experimental evaluations demonstrate that the distilled
models possess significantly stronger capabilities than their original
checkpoints. Additionally, we present use cases to illustrate the applications
of our framework in real-world scenarios. To facilitate practical use, we have
released all the DistilQwen2.5 models to the open-source community.
