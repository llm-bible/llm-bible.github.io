---
layout: publication
title: 'Neobert: A Next-generation BERT'
authors: Lola Le Breton, Quentin Fournier, Mariam El Mezouar, Sarath Chandar
conference: "Arxiv"
year: 2025
bibkey: breton2025next
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19587'}
tags: ['RAG', 'Tools', 'Applications', 'Model Architecture', 'Fine-Tuning', 'Training Techniques', 'BERT', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'In-Context Learning', 'Pretraining Methods']
---
Recent innovations in architecture, pre-training, and fine-tuning have led to
the remarkable in-context learning and reasoning abilities of large
auto-regressive language models such as LLaMA and DeepSeek. In contrast,
encoders like BERT and RoBERTa have not seen the same level of progress despite
being foundational for many downstream NLP applications. To bridge this gap, we
introduce NeoBERT, a next-generation encoder that redefines the capabilities of
bidirectional models by integrating state-of-the-art advancements in
architecture, modern data, and optimized pre-training methodologies. NeoBERT is
designed for seamless adoption: it serves as a plug-and-play replacement for
existing base models, relies on an optimal depth-to-width ratio, and leverages
an extended context length of 4,096 tokens. Despite its compact 250M parameter
footprint, it achieves state-of-the-art results on the massive MTEB benchmark,
outperforming BERT large, RoBERTa large, NomicBERT, and ModernBERT under
identical fine-tuning conditions. In addition, we rigorously evaluate the
impact of each modification on GLUE and design a uniform fine-tuning and
evaluation framework for MTEB. We release all code, data, checkpoints, and
training scripts to accelerate research and real-world adoption.
