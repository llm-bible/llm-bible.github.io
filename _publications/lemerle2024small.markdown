---
layout: publication
title: Small45;e Small Language Model With Linear Attention For Efficient Speech Synthesis
authors: Lemerle Théodor, Obin Nicolas, Roebel Axel
conference: "Arxiv"
year: 2024
bibkey: lemerle2024small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04467"}
  - {name: "Code", url: "https://github.com/theodorblackbird/lina&#45;speech"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent advancements in text45;to45;speech (TTS) powered by language models have showcased remarkable capabilities in achieving naturalness and zero45;shot voice cloning. Notably the decoder45;only transformer is the prominent architecture in this domain. However transformers face challenges stemming from their quadratic complexity in sequence length impeding training on lengthy sequences and resource45;constrained hardware. Moreover they lack specific inductive bias with regards to the monotonic nature of TTS alignments. In response we propose to replace transformers with emerging recurrent architectures and introduce specialized cross45;attention mechanisms for reducing repeating and skipping issues. Consequently our architecture can be efficiently trained on long samples and achieve state45;of45;the45;art zero45;shot voice cloning against baselines of comparable size. Our implementation and demos are available at https://github.com/theodorblackbird/lina&#45;speech.
