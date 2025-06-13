---
layout: publication
title: 'Mixture-of-depths: Dynamically Allocating Compute In Transformer-based Language Models'
authors: David Raposo, Sam Ritter, Blake Richards, Timothy Lillicrap, Peter Conway Humphreys, Adam Santoro
conference: "Arxiv"
year: 2024
bibkey: raposo2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02258"}
tags: ['Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Transformer-based language models spread FLOPs uniformly across input
sequences. In this work we demonstrate that transformers can instead learn to
dynamically allocate FLOPs (or compute) to specific positions in a sequence,
optimising the allocation along the sequence for different layers across the
model depth. Our method enforces a total compute budget by capping the number
of tokens (\\(k\\)) that can participate in the self-attention and MLP computations
at a given layer. The tokens to be processed are determined by the network
using a top-\\(k\\) routing mechanism. Since \\(k\\) is defined a priori, this simple
procedure uses a static computation graph with known tensor sizes, unlike other
conditional computation techniques. Nevertheless, since the identities of the
\\(k\\) tokens are fluid, this method can expend FLOPs non-uniformly across the
time and model depth dimensions. Thus, compute expenditure is entirely
predictable in sum total, but dynamic and context-sensitive at the token-level.
Not only do models trained in this way learn to dynamically allocate compute,
they do so efficiently. These models match baseline performance for equivalent
FLOPS and wall-clock times to train, but require a fraction of the FLOPs per
forward pass, and can be upwards of 50% faster to step during post-training
sampling.
