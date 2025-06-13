---
layout: publication
title: 'Recursive Inference Scaling: A Winning Path To Scalable Inference In Language And Multimodal Systems'
authors: Ibrahim Alabdulmohsin, Xiaohua Zhai
conference: "Arxiv"
year: 2025
bibkey: alabdulmohsin2025recursive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07503"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Language Modeling', 'Model Architecture', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods', 'Scaling Laws', 'Multimodal Models']
---
Inspired by recent findings on the fractal geometry of language, we introduce
Recursive INference Scaling (RINS) as a complementary, plug-in recipe for
scaling inference time in language and multimodal systems. RINS is a particular
form of recursive depth that significantly outperforms +55 other variants,
including the recent "repeat-all-over" (RAO) strategy in Mobile LLM (Liu et
al., 2024) and latent recurrent thinking (Geiping et al., 2025). Unlike prior
works, we carry out our comparisons on a compute-matched regime, and
demonstrate that for a fixed model size and training compute budget, RINS
substantially improves language modeling performance. It also generalizes
beyond pure language tasks, delivering gains in multimodal systems, including a
+2% improvement in 0-shot ImageNet accuracy for SigLIP-B/16. Additionally, by
deriving data scaling laws, we show that RINS improves both the asymptotic
performance limits and the scaling exponents. More importantly, with
light-weight (linear) adapters (comprising <1% of model parameters) and
stochastic dropout, RINS offers a no-regret strategy, meaning that RINS-enabled
pretraining improves performance in language modeling even when recursive depth
is not applied at inference time. This corresponds to improving performance on
a training compute-, parameter-, and inference-matched regime, suggesting its
potential as a viable component of LLM pretraining!
