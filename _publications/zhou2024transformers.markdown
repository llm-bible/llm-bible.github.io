---
layout: publication
title: 'Transformers Learn Variable-order Markov Chains In-context'
authors: Ruida Zhou, Chao Tian, Suhas Diggavi
conference: "Arxiv"
year: 2024
bibkey: zhou2024transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05493"}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models have demonstrated impressive in-context learning (ICL)
capability. However, it is still unclear how the underlying transformers
accomplish it, especially in more complex scenarios. Toward this goal, several
recent works studied how transformers learn fixed-order Markov chains (FOMC) in
context, yet natural languages are more suitably modeled by variable-order
Markov chains (VOMC), i.e., context trees (CTs). In this work, we study the ICL
of VOMC by viewing language modeling as a form of data compression and focus on
small alphabets and low-order VOMCs. This perspective allows us to leverage
mature compression algorithms, such as context-tree weighting (CTW) and
prediction by partial matching (PPM) algorithms as baselines, the former of
which is Bayesian optimal for a class of CTW priors. We empirically observe a
few phenomena: 1) Transformers can indeed learn to compress VOMC in-context,
while PPM suffers significantly; 2) The performance of transformers is not very
sensitive to the number of layers, and even a two-layer transformer can learn
in-context quite well; and 3) Transformers trained and tested on non-CTW priors
can significantly outperform the CTW algorithm. To explain these phenomena, we
analyze the attention map of the transformers and extract two mechanisms, on
which we provide two transformer constructions: 1) A construction with \\(D+2\\)
layers that can mimic the CTW algorithm accurately for CTs of maximum order
\\(D\\), 2) A 2-layer transformer that utilizes the feed-forward network for
probability blending. One distinction from the FOMC setting is that a counting
mechanism appears to play an important role. We implement these synthetic
transformer layers and show that such hybrid transformers can match the ICL
performance of transformers, and more interestingly, some of them can perform
even better despite the much-reduced parameter sets.
