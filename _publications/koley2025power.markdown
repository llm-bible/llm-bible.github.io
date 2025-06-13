---
layout: publication
title: 'Power Law Guided Dynamic Sifting For Efficient Attention'
authors: Nirav Koley, Prajwal Singhania, Abhinav Bhatele
conference: "Arxiv"
year: 2025
bibkey: koley2025power
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05300"}
tags: ['Attention Mechanism', 'Prompting', 'Model Architecture', 'Reinforcement Learning']
---
Efficient inference on GPUs using large language models remains challenging due to memory bandwidth limitations, particularly during data transfers between High Bandwidth Memory (HBM) and SRAM in attention computations. Approximate attention methods address this issue by reducing computational and memory overhead but often rely on expensive top-\\(k\\) operations, which perform poorly on GPUs. We propose SiftAttention, a novel approximate attention method that replaces the top-\\(k\\) step with a computationally efficient element-wise filtering operation based on a threshold value. Our intuition for doing this is based on our empirical observation that the \\(\tau\\)-th quantile of attention scores follows a predictable power-law over sequential generation steps. Exploiting this insight, our approach dynamically estimates a threshold value per prompt at each generation step. Only attention scores above this threshold and their corresponding value vectors are loaded/used to compute the attention output, reducing data movement between HBM and SRAM. Our evaluation demonstrates that SiftAttention preserves model quality better than existing approximate attention methods while reducing memory bandwidth usage when loading value vectors.
