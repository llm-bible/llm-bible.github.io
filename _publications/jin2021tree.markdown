---
layout: publication
title: 'Tree Decomposition Attention For Amr-to-text Generation'
authors: Lisa Jin, Daniel Gildea
conference: "Arxiv"
year: 2021
bibkey: jin2021tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.12300"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Text generation from AMR requires mapping a semantic graph to a string that
it annotates. Transformer-based graph encoders, however, poorly capture vertex
dependencies that may benefit sequence prediction. To impose order on an
encoder, we locally constrain vertex self-attention using a graph's tree
decomposition. Instead of forming a full query-key bipartite graph, we restrict
attention to vertices in parent, subtree, and same-depth bags of a vertex. This
hierarchical context lends both sparsity and structure to vertex state updates.
We apply dynamic programming to derive a forest of tree decompositions,
choosing the most structurally similar tree to the AMR. Our system outperforms
a self-attentive baseline by 1.6 BLEU and 1.8 chrF++.
