---
layout: publication
title: 'Overcoming Vocabulary Constraints With Pixel-level Fallback'
authors: Jonas F. Lotz, Hendra Setiawan, Stephan Peitz, Yova Kementchedjhieva
conference: "Arxiv"
year: 2025
bibkey: lotz2025overcoming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02122"}
tags: ['Tokenization', 'Efficiency and Optimization', 'Training Techniques', 'RAG']
---
Subword tokenization requires balancing computational efficiency and
vocabulary coverage, which often leads to suboptimal performance on languages
and scripts not prioritized during training. We propose to augment pretrained
language models with a vocabulary-free encoder that generates input embeddings
from text rendered as pixels. Through experiments on English-centric language
models, we demonstrate that our approach substantially improves machine
translation performance and facilitates effective cross-lingual transfer,
outperforming tokenizer-based methods. Furthermore, we find that pixel-based
representations outperform byte-level approaches and standard vocabulary
expansion. Our approach enhances the multilingual capabilities of monolingual
language models without extensive retraining and reduces decoding latency via
input compression.
