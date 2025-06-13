---
layout: publication
title: 'One Pass Streaming Algorithm For Super Long Token Attention Approximation In Sublinear Space'
authors: Raghav Addanki, Chenyang Li, Zhao Song, Chiwun Yang
conference: "Arxiv"
year: 2023
bibkey: addanki2023one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.14652"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Transformer', 'Applications', 'Attention Mechanism']
---
Attention computation takes both the time complexity of \\(O(n^2)\\) and the
space complexity of \\(O(n^2)\\) simultaneously, which makes deploying Large
Language Models (LLMs) in streaming applications that involve long contexts
requiring substantial computational resources. In recent OpenAI DevDay (Nov 6,
2023), OpenAI released a new model that is able to support a 128K-long
document, in our paper, we focus on the memory-efficient issue when context
length \\(n\\) is much greater than 128K (\\(n \gg 2^d\\)). Considering a single-layer
self-attention with Query, Key, and Value matrices \\(Q, K, V \in \mathbb\{R\}^\{n
\times d\}\\), the polynomial method approximates the attention output \\(T \in
\mathbb\{R\}^\{n \times d\}\\). It accomplishes this by constructing \\(U_1, U_2 \in
\mathbb\{R\}^\{n \times t\}\\) to expedite attention \\(\{\sf Attn\}(Q, K, V)\\)
computation within \\(n^\{1+o(1)\}\\) time executions. Despite this, computing the
approximated attention matrix \\(U_1U_2^\top \in \mathbb\{R\}^\{n \times n\}\\) still
necessitates \\(O(n^2)\\) space, leading to significant memory usage. In response
to these challenges, we introduce a new algorithm that only reads one pass of
the data in a streaming fashion. This method employs sublinear space \\(o(n)\\) to
store three sketch matrices, alleviating the need for exact \\(K, V\\) storage.
Notably, our algorithm exhibits exceptional memory-efficient performance with
super-long tokens. As the token length \\(n\\) increases, our error guarantee
diminishes while the memory usage remains nearly constant. This unique
attribute underscores the potential of our technique in efficiently handling
LLMs in streaming applications.
