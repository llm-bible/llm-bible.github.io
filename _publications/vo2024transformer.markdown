---
layout: publication
title: 'Transformer Layer Injection: A Novel Approach For Efficient Upscaling Of Large Language Models'
authors: James Vo
conference: "Arxiv"
year: 2024
bibkey: vo2024transformer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.11654'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
In this paper, we propose Transformer Layer Injection (TLI), a novel method
for efficiently upscaling large language models (LLMs) while minimizing
computational costs and maintaining model performance. Model scale is a key
factor in enhancing the quality of machine learning models, and TLI addresses
the challenge of scaling by reducing initial loss, minimizing fine-tuning
requirements, and preserving model complexity. Our approach improves upon the
conventional Depth Up-Scaling (DUS) technique by injecting new layers into
every set of K layers, enabling hidden representations to pass through
transformer blocks with minimal disruption. We compare TLI with existing
approaches, including Mixture of Experts (MoE) and DUS, and validate its
efficiency through experiments on small LLMs (LLama3 1B, 3B, and 8B). Results
show that TLI achieves better initialization, requires fewer training steps,
and delivers superior accuracy on tasks such as KoBEST and KMCQA, with models
performing effectively even without additional training. TLI is demonstrated to
be both data-efficient and cost-effective, significantly outperforming existing
methods. Its scalability and simplicity make it a promising solution for
upscaling transformer-based models, with potential applications in scaling
models from 10B to 405B parameters.
