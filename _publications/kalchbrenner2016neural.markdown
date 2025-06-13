---
layout: publication
title: 'Neural Machine Translation In Linear Time'
authors: Nal Kalchbrenner, Lasse Espeholt, Karen Simonyan, Aaron Van Den Oord, Alex Graves, Koray Kavukcuoglu
conference: "Arxiv"
year: 2016
bibkey: kalchbrenner2016neural
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1610.10099'}
tags: ['Attention Mechanism', 'WMT', 'Applications', 'Model Architecture']
---
We present a novel neural network for processing sequences. The ByteNet is a
one-dimensional convolutional neural network that is composed of two parts, one
to encode the source sequence and the other to decode the target sequence. The
two network parts are connected by stacking the decoder on top of the encoder
and preserving the temporal resolution of the sequences. To address the
differing lengths of the source and the target, we introduce an efficient
mechanism by which the decoder is dynamically unfolded over the representation
of the encoder. The ByteNet uses dilation in the convolutional layers to
increase its receptive field. The resulting network has two core properties: it
runs in time that is linear in the length of the sequences and it sidesteps the
need for excessive memorization. The ByteNet decoder attains state-of-the-art
performance on character-level language modelling and outperforms the previous
best results obtained with recurrent networks. The ByteNet also achieves
state-of-the-art performance on character-to-character machine translation on
the English-to-German WMT translation task, surpassing comparable neural
translation models that are based on recurrent networks with attentional
pooling and run in quadratic time. We find that the latent alignment structure
contained in the representations reflects the expected alignment between the
tokens.
