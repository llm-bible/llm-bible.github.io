---
layout: publication
title: 'Franken-adapter: Cross-lingual Adaptation Of Llms By Embedding Surgery'
authors: Fan Jiang, Honglin Yu, Grace Chung, Trevor Cohn
conference: "Arxiv"
year: 2025
bibkey: jiang2025franken
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08037"}
tags: ['Efficiency and Optimization']
---
The capabilities of Large Language Models (LLMs) in low-resource languages
lag far behind those in English, making their universal accessibility a
significant challenge. To alleviate this, we present
\\(\textit\{Franken-Adapter\}\\), a modular language adaptation approach for
decoder-only LLMs with embedding surgery. Our method begins by creating
customized vocabularies for target languages and performing language adaptation
through embedding tuning on multilingual data. These pre-trained embeddings are
subsequently integrated with LLMs that have been instruction-tuned on English
alignment data to enable zero-shot cross-lingual transfer. Our experiments on
\\(\texttt\{Gemma2\}\\) models with up to 27B parameters demonstrate improvements of
up to 20% across 96 languages, spanning both discriminative and generative
tasks, with minimal regressions (\\(<\\)1%) in English. Further in-depth analysis
reveals the critical role of customizing tokenizers in enhancing language
adaptation, while boosting inference efficiency. Additionally, we show the
versatility of our method by achieving a 14% improvement over a math-optimized
LLM across 20 languages, offering a modular solution to transfer reasoning
abilities across languages post hoc.
