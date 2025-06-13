---
layout: publication
title: 'HARP: Hesitation-aware Reframing In Transformer Inference Pass'
authors: Romain Storaï, Seung-won Hwang
conference: "Arxiv"
year: 2024
bibkey: storaï2024hesitation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07282'}
tags: ['Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
This paper aims to improve the performance of large language models by addressing the variable computational demands in inference steps, where some tokens require more computational resources than others. We present HARP, a simple modification to "off-the-shelf" Transformer forward pass. Drawing from hesitation and the framing effect in decision-making, HARP selectively applies additional computation when the model encounters uncertainty during token generation. Our method mimics human cognitive processes by pausing at difficult decision points and reframing inputs for a different perspective. Unlike other approaches, HARP is model-agnostic, training-free, and easy to implement. We evaluate our method across various downstream tasks and model sizes, demonstrating performance improvements up to +5.16%. Notably, HARP achieves these gains while maintaining inference times twice faster than beam search. Simple and yet with significant gains, HARP provides insights into the potential of adaptive computation for enhancing the performance of Transformer-based language models.
