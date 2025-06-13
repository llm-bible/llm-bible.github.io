---
layout: publication
title: 'DRAMA: Diverse Augmentation From Large Language Models To Smaller Dense Retrievers'
authors: Xueguang Ma, Xi Victoria Lin, Barlas Oguz, Jimmy Lin, Wen-tau Yih, Xilun Chen
conference: "Arxiv"
year: 2025
bibkey: ma2025diverse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18460'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated strong effectiveness and robustness while fine-tuned as dense retrievers. However, their large parameter size brings significant inference time computational challenges, including high encoding costs for large-scale corpora and increased query latency, limiting their practical deployment. While smaller retrievers offer better efficiency, they often fail to generalize effectively with limited supervised fine-tuning data. In this work, we introduce DRAMA, a training framework that leverages LLMs to train smaller generalizable dense retrievers. In particular, we adopt pruned LLMs as the backbone and train on diverse LLM-augmented data in a single-stage contrastive learning setup. Experiments show that DRAMA offers better multilingual and long-context capabilities than traditional encoder-based retrievers, and achieves strong performance across multiple tasks and languages. These highlight the potential of connecting the training of smaller retrievers with the growing advancements in LLMs, bridging the gap between efficiency and generalization.
