---
layout: publication
title: 'Deltazip: Multi-tenant Language Model Serving Via Delta Compression'
authors: Yao Xiaozhe, Klimovic Ana
conference: "Arxiv"
year: 2023
bibkey: yao2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05215"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Fine-tuning large language models (LLMs) for downstream tasks can greatly improve model quality however serving many different fine-tuned LLMs concurrently for users in multi-tenant environments is challenging. Dedicating GPU memory for each model is prohibitively expensive and naively swapping large model weights in and out of GPU memory is slow. Our key insight is that fine-tuned models can be quickly swapped in and out of GPU memory by extracting and compressing the delta between each model and its pre-trained base model. We propose DeltaZip an LLM serving system that efficiently serves multiple full-parameter fine-tuned models concurrently by aggressively compressing model deltas by a factor of (6times) to (8times) while maintaining high model quality. DeltaZip increases serving throughput by (1.5times) to (3times) and improves SLO attainment compared to a vanilla HuggingFace serving system.
