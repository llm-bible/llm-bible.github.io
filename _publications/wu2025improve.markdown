---
layout: publication
title: 'Improve Decoding Factuality By Token-wise Cross Layer Entropy Of Large Language Models'
authors: Jialiang Wu, Yi Shen, Sijia Liu, Yi Tang, Sen Song, Xiaoyi Wang, Longjun Cai
conference: "Arxiv"
year: 2025
bibkey: wu2025improve
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03199"}
tags: ['RAG', 'Training Techniques', 'Fine-Tuning']
---
Despite their impressive capacities, Large language models (LLMs) often
struggle with the hallucination issue of generating inaccurate or fabricated
content even when they possess correct knowledge. In this paper, we extend the
exploration of the correlation between hidden-state prediction changes and
output factuality into a deeper, token-wise level. Based on the insights , we
propose cross-layer Entropy eNhanced Decoding (END), a decoding method that
mitigates hallucinations without requiring extra training. END leverages inner
probability changes across layers to individually quantify the factual
knowledge required for each candidate token, and adjusts the final predicting
distribution to prioritize tokens with higher factuality. Experiments on both
hallucination and QA benchmarks demonstrate that END significantly enhances the
truthfulness and informativeness of generated content while maintaining robust
QA accuracy. Moreover, our work provides a deeper perspective on understanding
the correlations between inherent knowledge and output factuality.
