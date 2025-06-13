---
layout: publication
title: 'Rotary Outliers And Rotary Offset Features In Large Language Models'
authors: André Jonasson
conference: "Arxiv"
year: 2025
bibkey: jonasson2025rotary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01832"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer', 'Attention Mechanism']
---
Transformer-based Large Language Models (LLMs) rely on positional encodings
to provide sequence position information to their attention mechanism. Rotary
Positional Encodings (RoPE), which encode relative position by rotating queries
and keys, have become widely used in modern LLMs. We study the features and
patterns that emerge in queries and keys when using rotary embeddings. Our
analysis reveals consistent patterns within the same model across layers and
attention heads and across different models and architectures. We present and
apply analysis techniques and show how the queries and keys use RoPE to
construct various attention patterns, including attention sinks. We find and
analyze outliers across models in queries and keys and find that they are
likely to be found in rotary features with partial cycles. We derive bounds
that tell us what rotary frequencies are likely to be selected as outlier
features and at what minimum angle the query-key rotary pairs in these features
tend to be above and verify the bounds empirically with models of significant
architectural differences.
