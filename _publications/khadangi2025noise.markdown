---
layout: publication
title: 'Noise Augmented Fine Tuning For Mitigating Hallucinations In Large Language Models'
authors: Afshin Khadangi, Amir Sartipi, Igor Tchappi, Ramin Bahmani
conference: "Arxiv"
year: 2025
bibkey: khadangi2025noise
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03302"}
tags: ['Security', 'Training Techniques', 'Tools', 'Language Modeling', 'RAG', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning']
---
Large language models (LLMs) often produce inaccurate or misleading
content-hallucinations. To address this challenge, we introduce Noise-Augmented
Fine-Tuning (NoiseFiT), a novel framework that leverages adaptive noise
injection based on the signal-to-noise ratio (SNR) to enhance model robustness.
In particular, NoiseFiT selectively perturbs layers identified as either
high-SNR (more robust) or low-SNR (potentially under-regularized) using a
dynamically scaled Gaussian noise. We further propose a hybrid loss that
combines standard cross-entropy, soft cross-entropy, and consistency
regularization to ensure stable and accurate outputs under noisy training
conditions. Our theoretical analysis shows that adaptive noise injection is
both unbiased and variance-preserving, providing strong guarantees for
convergence in expectation. Empirical results on multiple test and benchmark
datasets demonstrate that NoiseFiT significantly reduces hallucination rates,
often improving or matching baseline performance in key tasks. These findings
highlight the promise of noise-driven strategies for achieving robust,
trustworthy language modeling without incurring prohibitive computational
overhead. Given the comprehensive and detailed nature of our experiments, we
have publicly released the fine-tuning logs, benchmark evaluation artifacts,
and source code online at W&B, Hugging Face, and GitHub, respectively, to
foster further research, accessibility and reproducibility.
