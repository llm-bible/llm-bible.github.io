---
layout: publication
title: 'Synthesizing And Adapting Error Correction Data For Mobile Large Language Model Applications'
authors: Yanxiang Zhang, Zheng Xu, Shanshan Wu, Yuanbo Zhang, Daniel Ramage
conference: "Arxiv"
year: 2025
bibkey: zhang2025synthesizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18488"}
tags: ['Prompting', 'Applications']
---
Error correction is an important capability when applying large language models (LLMs) to facilitate user typing on mobile devices. In this paper, we use LLMs to synthesize a high-quality dataset of error correction pairs to evaluate and improve LLMs for mobile applications. We first prompt LLMs with error correction domain knowledge to build a scalable and reliable addition to the existing data synthesis pipeline. We then adapt the synthetic data distribution to match the mobile application domain by reweighting the samples. The reweighting model is learnt by predicting (a handful of) live A/B test metrics when deploying LLMs in production, given the LLM performance on offline evaluation data and scores from a small privacy-preserving on-device language model. Finally, we present best practices for mixing our synthetic data with other data sources to improve model performance on error correction in both offline evaluation and production live A/B testing.
