---
layout: publication
title: "Hierarchical Transformers Are More Efficient Language Models"
authors: Nawrot Piotr, Tworkowski Szymon, Tyrolski Michał, Kaiser Łukasz, Wu Yuhuai, Szegedy Christian, Michalewski Henryk
conference: "Arxiv"
year: 2021
bibkey: nawrot2021hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.13711"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Transformer models yield impressive results on many NLP and sequence modeling tasks. Remarkably Transformers can handle long sequences which allows them to produce long coherent outputs full paragraphs produced by GPT-3 or well-structured images produced by DALL-E. These large language models are impressive but also very inefficient and costly which limits their applications and accessibility. We postulate that having an explicit hierarchical architecture is the key to Transformers that efficiently handle long sequences. To verify this claim we first study different ways to downsample and upsample activations in Transformers so as to make them hierarchical. We use the best performing upsampling and downsampling layers to create Hourglass - a hierarchical Transformer language model. Hourglass improves upon the Transformer baseline given the same amount of computation and can yield the same results as Transformers more efficiently. In particular Hourglass sets new state-of-the-art for Transformer models on the ImageNet32 generation task and improves language modeling efficiency on the widely studied enwik8 benchmark.
