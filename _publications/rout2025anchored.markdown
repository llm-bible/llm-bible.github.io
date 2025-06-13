---
layout: publication
title: 'Anchored Diffusion Language Model'
authors: Litu Rout, Constantine Caramanis, Sanjay Shakkottai
conference: "Arxiv"
year: 2025
bibkey: rout2025anchored
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18456"}
tags: ['Tools', 'GPT', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Diffusion Language Models (DLMs) promise parallel generation and bidirectional context, yet they underperform autoregressive (AR) models in both likelihood modeling and generated text quality. We identify that this performance gap arises when important tokens (e.g., key words or low-frequency words that anchor a sentence) are masked early in the forward process, limiting contextual information for accurate reconstruction. To address this, we introduce the Anchored Diffusion Language Model (ADLM), a novel two-stage framework that first predicts distributions over important tokens via an anchor network, and then predicts the likelihoods of missing tokens conditioned on the anchored predictions. ADLM significantly improves test perplexity on LM1B and OpenWebText, achieving up to 25.4% gains over prior DLMs, and narrows the gap with strong AR baselines. It also achieves state-of-the-art performance in zero-shot generalization across seven benchmarks and surpasses AR models in MAUVE score, which marks the first time a DLM generates better human-like text than an AR model. Theoretically, we derive an Anchored Negative Evidence Lower Bound (ANELBO) objective and show that anchoring improves sample complexity and likelihood modeling. Beyond diffusion, anchoring boosts performance in AR models and enhances reasoning in math and logic tasks, outperforming existing chain-of-thought approaches
