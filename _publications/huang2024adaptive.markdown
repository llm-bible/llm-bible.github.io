---
layout: publication
title: 'Moce: Adaptive Mixture Of Contextualization Experts For Byte-based Neural Machine Translation'
authors: Langlin Huang, Mengyu Bu, Yang Feng
conference: "Arxiv"
year: 2024
bibkey: huang2024adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.01474'}
  - {name: "Code", url: 'https://github.com/ictnlp/MoCE'}
tags: ['Attention Mechanism', 'Has Code', 'Applications', 'Model Architecture', 'Tokenization']
---
Byte-based machine translation systems have shown significant potential in
massively multilingual settings. Unicode encoding, which maps each character to
specific byte(s), eliminates the emergence of unknown words, even in new
languages. This avoids out-of-vocabulary risk in multilingual translation and
enables broad language scalability. However, byte-level tokenization results in
sequences that are hard to interpret due to limited semantic information per
byte. Local contextualization has proven effective in assigning initial
semantics to tokens, improving sentence comprehension. Nevertheless, variations
in encoding rules across languages necessitate an adaptive approach for
effective contextualization. To this end, we propose Mixture of
Contextualization Experts (MoCE), adaptively selecting and mixing attention
heads, which are treated as contextualization experts. This enhances the
flexibility of contextualization scales and allows models to search for better
contextualization combinations. Experiment results show that our method
outperforms existing methods without extensive manual adjustment of
hyper-parameters and surpasses subword-based models with fewer parameters in
Ted-59 dataset. Our code is available at https://github.com/ictnlp/MoCE.
