---
layout: publication
title: 'Probing Context Localization Of Polysemous Words In Pre-trained Language Model Sub-layers'
authors: Soniya Vijayakumar, Josef Van Genabith, Simon Ostermann
conference: "Arxiv"
year: 2024
bibkey: vijayakumar2024probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.14097"}
tags: ['Model Architecture', 'Reinforcement Learning', 'BERT', 'Transformer', 'Attention Mechanism']
---
In the era of high performing Large Language Models, researchers have widely
acknowledged that contextual word representations are one of the key drivers in
achieving top performances in downstream tasks. In this work, we investigate
the degree of contextualization encoded in the fine-grained sub-layer
representations of a Pre-trained Language Model (PLM) by empirical experiments
using linear probes. Unlike previous work, we are particularly interested in
identifying the strength of contextualization across PLM sub-layer
representations (i.e. Self-Attention, Feed-Forward Activation and Output
sub-layers). To identify the main contributions of sub-layers to
contextualisation, we first extract the sub-layer representations of polysemous
words in minimally different sentence pairs, and compare how these
representations change through the forward pass of the PLM network. Second, by
probing on a sense identification classification task, we try to empirically
localize the strength of contextualization information encoded in these
sub-layer representations. With these probing experiments, we also try to gain
a better understanding of the influence of context length and context richness
on the degree of contextualization. Our main conclusion is cautionary: BERT
demonstrates a high degree of contextualization in the top sub-layers if the
word in question is in a specific position in the sentence with a shorter
context window, but this does not systematically generalize across different
word positions and context sizes.
