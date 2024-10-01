---
layout: publication
title: 'Detecting Unintended Memorization In Language-model-fused ASR'
authors: Huang W. Ronny, Chien Steve, Thakkar Om, Mathews Rajiv
conference: "Arxiv"
year: 2022
bibkey: huang2022detecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.09606"}
tags: ['Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
End-to-end (E2E) models are often being accompanied by language models (LMs) via shallow fusion for boosting their overall quality as well as recognition of rare words. At the same time, several prior works show that LMs are susceptible to unintentionally memorizing rare or unique sequences in the training data. In this work, we design a framework for detecting memorization of random textual sequences (which we call canaries) in the LM training data when one has only black-box (query) access to LM-fused speech recognizer, as opposed to direct access to the LM. On a production-grade Conformer RNN-T E2E model fused with a Transformer LM, we show that detecting memorization of singly-occurring canaries from the LM training data of 300M examples is possible. Motivated to protect privacy, we also show that such memorization gets significantly reduced by per-example gradient-clipped LM training without compromising overall quality.
