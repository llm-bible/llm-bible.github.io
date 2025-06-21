---
layout: publication
title: 'Adamct: Adaptive Mixture Of Cnn-transformer For Sequential Recommendation'
authors: Juyong Jiang et al.
conference: Arxiv
year: 2022
citations: 29
bibkey: jiang2022adaptive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.08776'}, {name: Code,
    url: 'https://github.com/juyongjiang/AdaMCT'}]
tags: [Transformer, Efficiency and Optimization, Model Architecture]
---
Sequential recommendation (SR) aims to model users dynamic preferences from a
series of interactions. A pivotal challenge in user modeling for SR lies in the
inherent variability of user preferences. An effective SR model is expected to
capture both the long-term and short-term preferences exhibited by users,
wherein the former can offer a comprehensive understanding of stable interests
that impact the latter. To more effectively capture such information, we
incorporate locality inductive bias into the Transformer by amalgamating its
global attention mechanism with a local convolutional filter, and adaptively
ascertain the mixing importance on a personalized basis through layer-aware
adaptive mixture units, termed as AdaMCT. Moreover, as users may repeatedly
browse potential purchases, it is expected to consider multiple relevant items
concurrently in long-/short-term preferences modeling. Given that softmax-based
attention may promote unimodal activation, we propose the Squeeze-Excitation
Attention (with sigmoid activation) into SR models to capture multiple
pertinent items (keys) simultaneously. Extensive experiments on three widely
employed benchmarks substantiate the effectiveness and efficiency of our
proposed approach. Source code is available at
https://github.com/juyongjiang/AdaMCT.