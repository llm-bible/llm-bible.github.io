---
layout: publication
title: "Finding The Needle In A Haystack: Unsupervised Rationale Extraction From Long Text Classifiers"
authors: Bujel Kamil, Caines Andrew, Yannakoudakis Helen, Rei Marek
conference: "Arxiv"
year: 2023
bibkey: bujel2023finding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.07991"}
tags: ['Attention Mechanism', 'BERT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Long-sequence transformers are designed to improve the representation of longer texts by language models and their performance on downstream document-level tasks. However not much is understood about the quality of token-level predictions in long-form models. We investigate the performance of such architectures in the context of document classification with unsupervised rationale extraction. We find standard soft attention methods to perform significantly worse when combined with the Longformer language model. We propose a compositional soft attention architecture that applies RoBERTa sentence-wise to extract plausible rationales at the token-level. We find this method to significantly outperform Longformer-driven baselines on sentiment classification datasets while also exhibiting significantly lower runtimes.
