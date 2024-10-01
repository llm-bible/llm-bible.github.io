---
layout: publication
title: 'Breaking The Token Barrier: Chunking And Convolution For Efficient Long Text Classification With BERT'
authors: Jaiswal Aman, Milios Evangelos
conference: "Arxiv"
year: 2023
bibkey: jaiswal2023breaking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20558"}
tags: ['BERT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
"Transformer-based models, specifically BERT, have propelled research in various NLP tasks. However, these models are limited to a maximum token limit of 512 tokens. Consequently, this makes it non-trivial to apply it in a practical setting with long input. Various complex methods have claimed to overcome this limit, but recent research questions the efficacy of these models across different classification tasks. These complex architectures evaluated on carefully curated long datasets perform at par or worse than simple baselines. In this work, we propose a relatively simple extension to vanilla BERT architecture called ChunkBERT that allows finetuning of any pretrained models to perform inference on arbitrarily long text. The proposed method is based on chunking token representations and CNN layers, making it compatible with any pre-trained BERT. We evaluate chunkBERT exclusively on a benchmark for comparing long-text classification models across a variety of tasks (including binary classification, multi-class classification, and multi-label classification). A BERT model finetuned using the ChunkBERT method performs consistently across long samples in the benchmark while utilizing only a fraction (6.25\&#37;) of the original memory footprint. These findings suggest that efficient finetuning and inference can be achieved through simple modifications to pre-trained BERT models."
