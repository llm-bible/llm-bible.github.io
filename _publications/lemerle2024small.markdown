---
layout: publication
title: 'Small-e: Small Language Model With Linear Attention For Efficient Speech Synthesis'
authors: Lemerle Théodor, Obin Nicolas, Roebel Axel
conference: "Arxiv"
year: 2024
bibkey: lemerle2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04467"}
  - {name: "Code", url: "https://github.com/theodorblackbird/lina-speech"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent advancements in text-to-speech (TTS) powered by language models have showcased remarkable capabilities in achieving naturalness and zero-shot voice cloning. Notably, the decoder-only transformer is the prominent architecture in this domain. However, transformers face challenges stemming from their quadratic complexity in sequence length, impeding training on lengthy sequences and resource-constrained hardware. Moreover they lack specific inductive bias with regards to the monotonic nature of TTS alignments. In response, we propose to replace transformers with emerging recurrent architectures and introduce specialized cross-attention mechanisms for reducing repeating and skipping issues. Consequently our architecture can be efficiently trained on long samples and achieve state-of-the-art zero-shot voice cloning against baselines of comparable size. Our implementation and demos are available at https://github.com/theodorblackbird/lina-speech.
