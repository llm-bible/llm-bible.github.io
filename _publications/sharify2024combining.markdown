---
layout: publication
title: Combining multiple post-training techniques to achieve most efficient quantized LLMs
authors: Sharify Sayeh, Xu Zifei, Yazar Wanzin, Wang Xin
conference: "Arxiv"
year: 2024
bibkey: sharify2024combining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.07135"}
tags: ['ARXIV', 'GPT', 'LLM', 'Language Modeling', 'Quantization', 'RAG', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have distinguished themselves with outstanding performance in complex language modeling tasks yet they come with significant computational and storage challenges. This paper explores the potential of quantization to mitigate these challenges. We systematically study the combined application of two well-known post-training techniques SmoothQuant and GPTQ and provide a comprehensive analysis of their interactions and implications for advancing LLM quantization. We enhance the versatility of both techniques by enabling quantization to microscaling (MX) formats expanding their applicability beyond their initial fixed-point format targets. We show that by applying GPTQ and SmoothQuant and employing MX formats for quantizing models we can achieve a significant reduction in the size of OPT models by up to 4x and LLaMA models by up to 3x with a negligible perplexity increase of 1-3.
