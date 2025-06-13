---
layout: publication
title: 'Top-theta Attention: Sparsifying Transformers By Compensated Thresholding'
authors: Konstantin Berestizshevsky, Renzo Andri, Lukas Cavigelli
conference: "Arxiv"
year: 2025
bibkey: berestizshevsky2025top
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08363"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
The attention mechanism is essential for the impressive capabilities of
transformer-based Large Language Models (LLMs). However, calculating attention
is computationally intensive due to its quadratic dependency on the sequence
length. We introduce a novel approach called Top-Theta Attention, or simply
Top-\\(\theta\\), which selectively prunes less essential attention elements by
comparing them against carefully calibrated thresholds. This method greatly
improves the efficiency of self-attention matrix multiplication while
preserving model accuracy, reducing the number of required V cache rows by 3x
during generative decoding and the number of attention elements by 10x during
the prefill phase. Our method does not require model retraining; instead, it
requires only a brief calibration phase to be resilient to distribution shifts,
thus not requiring the thresholds for different datasets to be recalibrated.
Unlike top-k attention, Top-\\(\theta\\) eliminates full-vector dependency, making
it suitable for tiling and scale-out and avoiding costly top-k search. A key
innovation of our approach is the development of efficient numerical
compensation techniques, which help preserve model accuracy even under
aggressive pruning of attention scores.
