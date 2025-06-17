---
layout: publication
title: Location-relative Attention Mechanisms For Robust Long-form Speech Synthesis
authors: Eric Battenberg et al.
conference: Arxiv
year: 2019
citations: 51
bibkey: battenberg2019location
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.10288'}]
tags: [Transformer, Attention Mechanism]
---
Despite the ability to produce human-level speech for in-domain text,
attention-based end-to-end text-to-speech (TTS) systems suffer from text
alignment failures that increase in frequency for out-of-domain text. We show
that these failures can be addressed using simple location-relative attention
mechanisms that do away with content-based query/key comparisons. We compare
two families of attention mechanisms: location-relative GMM-based mechanisms
and additive energy-based mechanisms. We suggest simple modifications to
GMM-based attention that allow it to align quickly and consistently during
training, and introduce a new location-relative attention mechanism to the
additive energy-based family, called Dynamic Convolution Attention (DCA). We
compare the various mechanisms in terms of alignment speed and consistency
during training, naturalness, and ability to generalize to long utterances, and
conclude that GMM attention and DCA can generalize to very long utterances,
while preserving naturalness for shorter, in-domain utterances.