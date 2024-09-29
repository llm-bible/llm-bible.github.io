---
layout: publication
title: Leanquant Accurate Large Language Model Quantization With Loss-error-aware Grid
authors: Zhang Tianyi, Shrivastava Anshumali
conference: "Arxiv"
year: 2024
bibkey: zhang2024accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10032"}
tags: ['Applications', 'Efficiency And Optimization', 'Quantization', 'RAG', 'Tools']
---
Large language models (LLMs) have numerous applications across various domains but their high computational and memory demands pose significant deployment challenges. Weight quantization is an effective technique for reducing the decoding latency and memory requirements of LLMs. Existing approaches primarily aim to maintain the quality of quantized models by preserving outliers in input features but they still suffer significant quality loss at lower bit widths. Our approach builds on Optimal Brain Quantization (OBQ) an iterative weight-update-based quantization framework. We identify a key limitation of OBQ specifically that its uniform quantization grid is suboptimal for maintaining model quality as it introduces large errors to the task loss. To address this we propose LeanQuant which learns a loss-error-aware quantization grid by leveraging the inverse diagonal Hessian. Extensive empirical evaluations demonstrate that LeanQuant is both efficient and accurate; it can quantize a 70-billion-parameter model in 6 hours using a single 32GB GPU and performs favorably compared to competitive baselines in the 4-bit 3-bit and 2-bit regions.
