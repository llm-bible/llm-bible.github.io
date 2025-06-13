---
layout: publication
title: 'Stream Aligner: Efficient Sentence-level Alignment Via Distribution Induction'
authors: Hantao Lou, Jiaming Ji, Kaile Wang, Yaodong Yang
conference: "Arxiv"
year: 2025
bibkey: lou2025stream
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.05336"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools']
---
The rapid advancement of large language models (LLMs) has led to significant
improvements in their capabilities, but also to increased concerns about their
alignment with human values and intentions. Current alignment strategies,
including adaptive training and inference-time methods, have demonstrated
potential in this area. However, these approaches still struggle to balance
deployment complexity and capability across various tasks and difficulties. In
this work, we introduce the Streaming Distribution Induce Aligner (Stream
Aligner), a novel alignment paradigm that combines efficiency with enhanced
performance in various tasks throughout the generation process. Stream Aligner
achieves dynamic sentence-level correction by using a small model to learn the
preferences of the suffix sentence, iteratively correcting the suffix sentence
output by the upstream model, and then using the corrected sentence to replace
the suffix sentence in subsequent generations. Compared to Aligner, our
experiments demonstrate that Stream Aligner reduces reliance on the
capabilities of additional models, enhances the reasoning abilities of LLMs,
and decreases latency during user interaction. Specifically, Stream Aligner-2B
model has achieved an improvement of 76.1% in helpfulness, 36.0% in
harmlessness on the tested Llama2-70B-chat model, and Stream Aligner-8B has
achieved an improvement of 3.5% on the math ability of the tested
Llama3-70B-Instruct model.
