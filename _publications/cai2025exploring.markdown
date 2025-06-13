---
layout: publication
title: 'Exploring Training And Inference Scaling Laws In Generative Retrieval'
authors: Hongru Cai, Yongqi Li, Ruifeng Yuan, Wenjie Wang, Zhen Zhang, Wenjie Li, Tat-seng Chua
conference: "Arxiv"
year: 2025
bibkey: cai2025exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18941"}
tags: ['Pre-Training', 'GPT', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods', 'Scaling Laws']
---
Generative retrieval has emerged as a novel paradigm that leverages large
language models (LLMs) to autoregressively generate document identifiers.
Although promising, the mechanisms that underpin its performance and
scalability remain largely unclear. We conduct a systematic investigation of
training and inference scaling laws in generative retrieval, exploring how
model size, training data scale, and inference-time compute jointly influence
retrieval performance. To address the lack of suitable metrics, we propose a
novel evaluation measure inspired by contrastive entropy and generation loss,
providing a continuous performance signal that enables robust comparisons
across diverse generative retrieval methods. Our experiments show that
n-gram-based methods demonstrate strong alignment with both training and
inference scaling laws, especially when paired with larger LLMs. Furthermore,
increasing inference computation yields substantial performance gains,
revealing that generative retrieval can significantly benefit from higher
compute budgets at inference. Across these settings, LLaMA models consistently
outperform T5 models, suggesting a particular advantage for larger decoder-only
models in generative retrieval. Taken together, our findings underscore that
model sizes, data availability, and inference computation interact to unlock
the full potential of generative retrieval, offering new insights for designing
and optimizing future systems.
