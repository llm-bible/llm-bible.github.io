---
layout: publication
title: 'Visual Attention Never Fades: Selective Progressive Attention Recalibration For Detailed Image Captioning In Multimodal Large Language Models'
authors: Mingi Jung, Saehyung Lee, Eunji Kim, Sungroh Yoon
conference: "Arxiv"
year: 2025
bibkey: jung2025visual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01419'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Model Architecture', 'Multimodal Models']
---
Detailed image captioning is essential for tasks like data generation and aiding visually impaired individuals. High-quality captions require a balance between precision and recall, which remains challenging for current multimodal large language models (MLLMs). In this work, we hypothesize that this limitation stems from weakening and increasingly noisy visual attention as responses lengthen. To address this issue, we propose SPARC (Selective Progressive Attention ReCalibration), a training-free method that enhances the contribution of visual tokens during decoding. SPARC is founded on three key observations: (1) increasing the influence of all visual tokens reduces recall; thus, SPARC selectively amplifies visual tokens; (2) as captions lengthen, visual attention becomes noisier, so SPARC identifies critical visual tokens by leveraging attention differences across time steps; (3) as visual attention gradually weakens, SPARC reinforces it to preserve its influence. Our experiments, incorporating both automated and human evaluations, demonstrate that existing methods improve the precision of MLLMs at the cost of recall. In contrast, our proposed method enhances both precision and recall with minimal computational overhead.
