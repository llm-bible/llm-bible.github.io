---
layout: publication
title: Dynamic Past And Future For Neural Machine Translation
authors: Zaixiang Zheng, Shujian Huang, Zhaopeng Tu, Xin-yu Dai, Jiajun Chen
conference: Arxiv
year: 2019
citations: 16
bibkey: zheng2019dynamic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09646'}]
tags: [Transformer, Model Architecture]
---
Previous studies have shown that neural machine translation (NMT) models can
benefit from explicitly modeling translated (Past) and untranslated (Future) to
groups of translated and untranslated contents through parts-to-wholes
assignment. The assignment is learned through a novel variant of
routing-by-agreement mechanism (Sabour et al., 2017), namely \{\em Guided
Dynamic Routing\}, where the translating status at each decoding step \{\em
guides\} the routing process to assign each source word to its associated group
(i.e., translated or untranslated content) represented by a capsule, enabling
translation to be made from holistic context. Experiments show that our
approach achieves substantial improvements over both RNMT and Transformer by
producing more adequate translations. Extensive analysis demonstrates that our
method is highly interpretable, which is able to recognize the translated and
untranslated contents as expected.