---
layout: publication
title: 'Semantic Retention And Extreme Compression In Llms: Can We Have Both?'
authors: Stanislas Laborde, Martin Cousseau, Antoun Yaacoub, Lionel Prevost
conference: "Arxiv"
year: 2025
bibkey: laborde2025semantic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.07289'}
tags: ['RAG', 'Efficiency and Optimization', 'Tools', 'Quantization', 'Pruning']
---
The exponential growth in Large Language Model (LLM) deployment has intensified the need for efficient model compression techniques to reduce computational and memory costs. While pruning and quantization have shown promise, their combined potential remains largely unexplored. In this paper, we examine joint compression and how strategically combining pruning and quantization could yield superior performance-to-compression ratios compared to single-method approaches. Recognizing the challenges in accurately assessing LLM performance, we address key limitations of previous evaluation frameworks and introduce the Semantic Retention Compression Rate (SrCr), a novel metric that quantifies the trade-off between model compression and semantic preservation, facilitating the optimization of pruning-quantization configurations. Experiments demonstrate that our recommended combination achieves, on average, a 20% performance increase compared to an equivalent quantization-only model at the same theoretical compression rate.
