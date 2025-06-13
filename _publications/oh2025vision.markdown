---
layout: publication
title: 'Vision-encoders (already) Know What They See: Mitigating Object Hallucination Via Simple Fine-grained Clipscore'
authors: Hongseok Oh, Wonseok Hwang
conference: "Arxiv"
year: 2025
bibkey: oh2025vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20034"}
tags: ['Multimodal Models', 'Training Techniques']
---
Recently, Large Vision-Language Models (LVLMs) show remarkable performance across various domains. However, these models suffer from object hallucination. This study revisits the previous claim that the primary cause of such hallucination lies in the limited representational capacity of the vision encoder. Our analysis reveals that the capacity of the vision encoder itself is already adequate for detecting object hallucination. Based on this insight, we propose a Fine-grained CLIPScore (F-CLIPScore), a simple yet effective evaluation metric that enhances object-level granularity by incorporating text embeddings at the noun level. Evaluations on the OHD-Caps benchmark show that F-CLIPScore significantly outperforms conventional CLIPScore in accuracy by a large margin of 39.6% without additional training. We further demonstrate that F-CLIPScore-based data filtering reduces object hallucination in LVLMs (4.9% in POPE).
