---
layout: publication
title: 'Shortcut-stacked Sentence Encoders For Multi-domain Inference'
authors: Nie Yixin, Bansal Mohit
conference: "Arxiv"
year: 2017
citations: 127
bibkey: nie2017shortcut
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1708.02312"}
tags: ['Fine-Tuning', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'EMNLP']
---
We present a simple sequential sentence encoder for multi-domain natural
language inference. Our encoder is based on stacked bidirectional LSTM-RNNs
with shortcut connections and fine-tuning of word embeddings. The overall
supervised model uses the above encoder to encode two input sentences into two
vectors, and then uses a classifier over the vector combination to label the
relationship between these two sentences as that of entailment, contradiction,
or neural. Our Shortcut-Stacked sentence encoders achieve strong improvements
over existing encoders on matched and mismatched multi-domain natural language
inference (top non-ensemble single-model result in the EMNLP RepEval 2017
Shared Task (Nangia et al., 2017)). Moreover, they achieve the new
state-of-the-art encoding result on the original SNLI dataset (Bowman et al.,
2015).
