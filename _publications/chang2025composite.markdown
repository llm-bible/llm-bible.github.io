---
layout: publication
title: 'CASIM: Composite Aware Semantic Injection For Text To Motion Generation'
authors: Che-jui Chang, Qingze Tony Liu, Honglu Zhou, Vladimir Pavlovic, Mubbasir Kapadia
conference: "Arxiv"
year: 2025
bibkey: chang2025composite
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02063'}
tags: ['RAG', 'GPT', 'Merging', 'Prompting', 'Tokenization', 'Pretraining Methods']
---
Recent advances in generative modeling and tokenization have driven
significant progress in text-to-motion generation, leading to enhanced quality
and realism in generated motions. However, effectively leveraging textual
information for conditional motion generation remains an open challenge. We
observe that current approaches, primarily relying on fixed-length text
embeddings (e.g., CLIP) for global semantic injection, struggle to capture the
composite nature of human motion, resulting in suboptimal motion quality and
controllability. To address this limitation, we propose the Composite Aware
Semantic Injection Mechanism (CASIM), comprising a composite-aware semantic
encoder and a text-motion aligner that learns the dynamic correspondence
between text and motion tokens. Notably, CASIM is model and
representation-agnostic, readily integrating with both autoregressive and
diffusion-based methods. Experiments on HumanML3D and KIT benchmarks
demonstrate that CASIM consistently improves motion quality, text-motion
alignment, and retrieval scores across state-of-the-art methods. Qualitative
analyses further highlight the superiority of our composite-aware approach over
fixed-length semantic injection, enabling precise motion control from text
prompts and stronger generalization to unseen text inputs.
