---
layout: publication
title: 'Long Context In-context Compression By Getting To The Gist Of Gisting'
authors: Aleksandar Petrov, Mark Sandler, Andrey Zhmoginov, Nolan Miller, Max Vladymyrov
conference: "Arxiv"
year: 2025
bibkey: petrov2025long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.08934"}
tags: ['Transformer', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods']
---
Long context processing is critical for the adoption of LLMs, but existing
methods often introduce architectural complexity that hinders their practical
adoption. Gisting, an in-context compression method with no architectural
modification to the decoder transformer, is a promising approach due to its
simplicity and compatibility with existing frameworks. While effective for
short instructions, we demonstrate that gisting struggles with longer contexts,
with significant performance drops even at minimal compression rates.
Surprisingly, a simple average pooling baseline consistently outperforms
gisting. We analyze the limitations of gisting, including information flow
interruptions, capacity limitations and the inability to restrict its attention
to subsets of the context. Motivated by theoretical insights into the
performance gap between gisting and average pooling, and supported by extensive
experimentation, we propose GistPool, a new in-context compression method.
GistPool preserves the simplicity of gisting, while significantly boosting its
performance on long context compression tasks.
