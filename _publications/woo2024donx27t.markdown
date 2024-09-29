---
layout: publication
title: Donx27;t Miss The Forest For The Trees Attentional Vision Calibration For Large Vision Language Models
authors: Woo Sangmin, Kim Donguk, Jang Jaehyuk, Choi Yubin, Kim Changick
conference: "Arxiv"
year: 2024
bibkey: woo2024donx27t
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17820"}
tags: ['Attention Mechanism', 'Model Architecture', 'Multimodal Models']
---
This study addresses the issue observed in Large Vision Language Models (LVLMs) where excessive attention on a few image tokens referred to as blind tokens leads to hallucinatory responses in tasks requiring fine-grained understanding of visual objects. We found that tokens receiving lower attention weights often hold essential information for identifying nuanced object details -- ranging from merely recognizing object existence to identifying their attributes (color position etc.) and understanding their relationships. To counteract the over-emphasis on blind tokens and to accurately respond to user queries we introduce a technique called Attentional Vision Calibration (AVC). During the decoding phase AVC identifies blind tokens by analyzing the image-related attention distribution. It then dynamically adjusts the logits for the next token prediction by contrasting the logits conditioned on the original visual tokens with those conditioned on the blind tokens. This effectively lowers the dependency on blind tokens and promotes a more balanced consideration of all tokens. We validate AVC on benchmarks such as POPE MME and AMBER where it consistently outperforms existing decoding techniques in mitigating object hallucinations in LVLMs.
