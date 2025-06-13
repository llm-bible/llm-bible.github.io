---
layout: publication
title: 'Improving Context-aware Neural Machine Translation With Target-side Context'
authors: Hayahide Yamagishi, Mamoru Komachi
conference: "Arxiv"
year: 2019
bibkey: yamagishi2019improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.00531"}
tags: ['Transformer', 'Attention Mechanism', 'Model Architecture', 'Applications']
---
In recent years, several studies on neural machine translation (NMT) have
attempted to use document-level context by using a multi-encoder and two
attention mechanisms to read the current and previous sentences to incorporate
the context of the previous sentences. These studies concluded that the
target-side context is less useful than the source-side context. However, we
considered that the reason why the target-side context is less useful lies in
the architecture used to model these contexts.
  Therefore, in this study, we investigate how the target-side context can
improve context-aware neural machine translation. We propose a weight sharing
method wherein NMT saves decoder states and calculates an attention vector
using the saved states when translating a current sentence. Our experiments
show that the target-side context is also useful if we plug it into NMT as the
decoder state when translating a previous sentence.
