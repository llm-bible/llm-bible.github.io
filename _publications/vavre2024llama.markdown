---
layout: publication
title: 'Llama 3 Meets Moe: Efficient Upcycling'
authors: Aditya Vavre, Ethan He, Dennis Liu, Zijie Yan, June Yang, Nima Tajbakhsh, Ashwath Aithal
conference: "Arxiv"
year: 2024
bibkey: vavre2024llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09952"}
tags: ['Training Techniques', 'RAG', 'Pre-Training', 'Tools']
---
Scaling large language models (LLMs) significantly improves performance but
comes with prohibitive computational costs. Mixture-of-Experts (MoE) models
offer an efficient alternative, increasing capacity without a proportional rise
in compute requirements. However, training MoE models from scratch poses
challenges like overfitting and routing instability. We present an efficient
training recipe leveraging pre-trained dense checkpoints, training an 8-Expert
Top-2 MoE model from Llama 3-8B with less than \\(1%\\) of typical pre-training
compute. Our approach enhances downstream performance on academic benchmarks,
achieving a \\(\textbf\{2%\}\\) improvement in 0-shot accuracy on MMLU, while
reaching a Model FLOPs Utilization (MFU) of \\(\textbf\{46.8%\}\\) during training
using our framework. We also integrate online upcycling in NeMo for seamless
use of pre-trained weights, enabling cost-effective development of
high-capacity MoE models.
