---
layout: publication
title: 'Post Training Quantization Of Large Language Models With Microscaling Formats'
authors: Sayeh Sharify, Utkarsh Saxena, Zifei Xu, Wanzin Yazar, Ilya Soloveychik, Xin Wang
conference: "Arxiv"
year: 2024
bibkey: sharify2024post
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.07135'}
tags: ['Language Modeling', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'GPT', 'Model Architecture', 'Quantization']
---
Large Language Models (LLMs) have distinguished themselves with outstanding
performance in complex language modeling tasks, yet they come with significant
computational and storage challenges. This paper explores the potential of
quantization to mitigate these challenges. We systematically study the combined
application of three well-known post-training techniques, SmoothQuant, AWQ, and
GPTQ, and provide a comprehensive analysis of their interactions and
implications for advancing LLM quantization. We enhance the versatility of
these methods by enabling quantization to microscaling (MX) formats, extending
the applicability of these PTQ algorithms beyond their original fixed-point
format targets. We show that combining different PTQ methods enables us to
quantize models to 4-bit weights and 8-bit activations using the MXINT format
with negligible accuracy loss compared to the uncompressed baseline.
