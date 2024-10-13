---
layout: publication
title: 'Adapting Monolingual Models: Data Can Be Scarce When Language Similarity Is High'
authors: De Vries Wietse, Bartelds Martijn, Nissim Malvina, Wieling Martijn
conference: "Findings of the Association for Computational Linguistics ACL-IJCNLP"
year: 2021
bibkey: devries2021adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.02855"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
For many (minority) languages, the resources needed to train large models are
not available. We investigate the performance of zero-shot transfer learning
with as little data as possible, and the influence of language similarity in
this process. We retrain the lexical layers of four BERT-based models using
data from two low-resource target language varieties, while the Transformer
layers are independently fine-tuned on a POS-tagging task in the model's source
language. By combining the new lexical layers and fine-tuned Transformer
layers, we achieve high task performance for both target languages. With high
language similarity, 10MB of data appears sufficient to achieve substantial
monolingual transfer performance. Monolingual BERT-based models generally
achieve higher downstream task performance after retraining the lexical layer
than multilingual BERT, even when the target language is included in the
multilingual model.
