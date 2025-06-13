---
layout: publication
title: 'Compression Laws For Large Language Models'
authors: Ayan Sengupta, Siddhant Chaudhary, Tanmoy Chakraborty
conference: "Arxiv"
year: 2025
bibkey: sengupta2025compression
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04342"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'Reinforcement Learning', 'Quantization', 'Pretraining Methods', 'Large-Scale Training', 'Fine-Tuning', 'Pre-Training', 'Applications']
---
We introduce compression laws for language language models (LLMs). While
recent scaling laws have sought to understand how LLMs scale with respect to
model size, pre-training data, and computational resources, we focus on
understanding how model compression affects the performance of a pre-trained
LLM on downstream tasks. We empirically examine the effects of structured model
compression on LLMs through over \\(1000\\) experiments across eight models with
sizes ranging from \\(0.5B\\) to \\(14B\\) parameters. Our findings indicate that the
test cross-entropy loss increases quadratically with the compression ratio,
whereas performance on downstream tasks declines only linearly. Our study
emphasizes the importance of recovery fine-tuning in enhancing generation loss,
showing that the test loss of compressed LLMs can improve by up to 55% with
recovery fine-tuning. At higher compression ratios (up to 90%), compressed LLMs
demonstrate a speed increase of 60% during inference compared to their
uncompressed counterparts, compensating for the performance degradation at this
level. However, for smaller models (\\(\le 7B\\)), the computational gains are
limited, peaking at just 35%. We conclude that model compression can be highly
beneficial for larger models, especially when a smaller model within the same
computational budget is not available. These insights provide the practical
guidelines for utilizing model compression techniques for adopting LLMs in
real-life applications in resource-constrained settings.
