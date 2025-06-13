---
layout: publication
title: 'You Do Not Fully Utilize Transformer''s Representation Capacity'
authors: Gleb Gerasimov, Yaroslav Aksenov, Nikita Balagansky, Viacheslav Sinii, Daniil Gavrilov
conference: "Arxiv"
year: 2025
bibkey: gerasimov2025you
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09245"}
tags: ['Model Architecture', 'Language Modeling', 'RAG', 'Pretraining Methods', 'Transformer']
---
In contrast to RNNs, which compress their history into a single hidden state, Transformers can attend to all past tokens directly. However, standard Transformers rely solely on the hidden state from the previous layer to represent the entire context. We show that this design choice induces representation collapse and degrades performance. To address this issue, we introduce Layer-Integrated Memory (LIMe), a lightweight extension that leverages existing key-value buffers and learns per-head, per-layer routing weights to integrate representations from all previous layers with negligible overhead. Through extensive experiments-including language modeling, synthetic reasoning benchmarks, and very deep architectures-LIMe consistently achieves faster convergence, lower perplexity per FLOP, and substantial accuracy improvements on synthetic tasks while preserving higher value-vector entropy and improved token separability. Finally, our analysis of the learned routing weights reveals systematic reuse of both local and long-distance features, demonstrating how LIMe mitigates collapse, unlocks richer representations without increasing hidden-state size, and points to promising directions for future research.
