---
layout: publication
title: 'Patch Matters: Training-free Fine-grained Image Caption Enhancement Via Local Perception'
authors: Ruotian Peng, Haiying He, Yake Wei, Yandong Wen, Di Hu
conference: "Arxiv"
year: 2025
bibkey: peng2025patch
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.06666'}
  - {name: "Code", url: 'https://github.com/GeWu-Lab/Patch-Matters'}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Applications', 'GPT', 'Training Techniques', 'Multimodal Models']
---
High-quality image captions play a crucial role in improving the performance
of cross-modal applications such as text-to-image generation, text-to-video
generation, and text-image retrieval. To generate long-form, high-quality
captions, many recent studies have employed multimodal large language models
(MLLMs). However, current MLLMs often produce captions that lack fine-grained
details or suffer from hallucinations, a challenge that persists in both
open-source and closed-source models. Inspired by Feature-Integration theory,
which suggests that attention must focus on specific regions to integrate
visual information effectively, we propose a \textbf\{divide-then-aggregate\}
strategy. Our method first divides the image into semantic and spatial patches
to extract fine-grained details, enhancing the model's local perception of the
image. These local details are then hierarchically aggregated to generate a
comprehensive global description. To address hallucinations and inconsistencies
in the generated captions, we apply a semantic-level filtering process during
hierarchical aggregation. This training-free pipeline can be applied to both
open-source models (LLaVA-1.5, LLaVA-1.6, Mini-Gemini) and closed-source models
(Claude-3.5-Sonnet, GPT-4o, GLM-4V-Plus). Extensive experiments demonstrate
that our method generates more detailed, reliable captions, advancing
multimodal description generation without requiring model retraining. The
source code are available at https://github.com/GeWu-Lab/Patch-Matters
