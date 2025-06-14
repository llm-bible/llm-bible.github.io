---
layout: publication
title: 'Linguistic Input Features Improve Neural Machine Translation'
authors: Rico Sennrich, Barry Haddow
conference: "Arxiv"
year: 2016
citations: 101
bibkey: sennrich2016linguistic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1606.02892'}
tags: ['Attention Mechanism', 'WMT', 'Training Techniques', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Neural machine translation has recently achieved impressive results, while
using little in the way of external linguistic information. In this paper we
show that the strong learning capability of neural MT models does not make
linguistic features redundant; they can be easily incorporated to provide
further improvements in performance. We generalize the embedding layer of the
encoder in the attentional encoder--decoder architecture to support the
inclusion of arbitrary features, in addition to the baseline word feature. We
add morphological features, part-of-speech tags, and syntactic dependency
labels as input features to English<->German, and English->Romanian neural
machine translation systems. In experiments on WMT16 training and test sets, we
find that linguistic input features improve model quality according to three
metrics: perplexity, BLEU and CHRF3. An open-source implementation of our
neural MT system is available, as are sample files and configurations.
