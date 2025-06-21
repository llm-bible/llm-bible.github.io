---
layout: publication
title: 'Seq2seq-vis: A Visual Debugging Tool For Sequence-to-sequence Models'
authors: Hendrik Strobelt et al.
conference: Arxiv
year: 2018
citations: 128
bibkey: strobelt2018visual
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.09299'}]
tags: [Applications, Language Modeling]
---
Neural Sequence-to-Sequence models have proven to be accurate and robust for
many sequence prediction tasks, and have become the standard approach for
automatic translation of text. The models work in a five stage blackbox process
that involves encoding a source sequence to a vector space and then decoding
out to a new target sequence. This process is now standard, but like many deep
learning methods remains quite difficult to understand or debug. In this work,
we present a visual analysis tool that allows interaction with a trained
sequence-to-sequence model through each stage of the translation process. The
aim is to identify which patterns have been learned and to detect model errors.
We demonstrate the utility of our tool through several real-world large-scale
sequence-to-sequence use cases.