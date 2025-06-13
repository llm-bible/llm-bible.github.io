---
layout: publication
title: 'Don''t Miss The Forest For The Trees: Attentional Vision Calibration For Large Vision Language Models'
authors: Sangmin Woo, Donguk Kim, Jaehyuk Jang, Yubin Choi, Changick Kim
conference: "Arxiv"
year: 2024
bibkey: woo2024miss
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17820"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Ethics and Bias', 'Transformer', 'Attention Mechanism']
---
Large Vision Language Models (LVLMs) demonstrate strong capabilities in visual understanding and description, yet often suffer from hallucinations, attributing incorrect or misleading features to images. We observe that LVLMs disproportionately focus on a small subset of image tokens--termed blind tokens--which are typically irrelevant to the query (e.g., background or non-object regions). We hypothesize that such attention misalignment plays a key role in generating hallucinated responses. To mitigate this issue, we propose Attentional Vision Calibration (AvisC), a test-time approach that dynamically recalibrates the influence of blind tokens without modifying the underlying attention mechanism. AvisC first identifies blind tokens by analyzing layer-wise attention distributions over image tokens, then employs a contrastive decoding strategy to balance the influence of original and blind-token-biased logits. Experiments on standard benchmarks, including POPE, MME, and AMBER, demonstrate that AvisC effectively reduces hallucinations in LVLMs.
