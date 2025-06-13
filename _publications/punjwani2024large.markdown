---
layout: publication
title: 'Large Body Language Models'
authors: Saif Punjwani, Larry Heck
conference: "Arxiv"
year: 2024
bibkey: punjwani2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16533"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Merging', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
As virtual agents become increasingly prevalent in human-computer
interaction, generating realistic and contextually appropriate gestures in
real-time remains a significant challenge. While neural rendering techniques
have made substantial progress with static scripts, their applicability to
human-computer interactions remains limited. To address this, we introduce
Large Body Language Models (LBLMs) and present LBLM-AVA, a novel LBLM
architecture that combines a Transformer-XL large language model with a
parallelized diffusion model to generate human-like gestures from multimodal
inputs (text, audio, and video). LBLM-AVA incorporates several key components
enhancing its gesture generation capabilities, such as multimodal-to-pose
embeddings, enhanced sequence-to-sequence mapping with redefined attention
mechanisms, a temporal smoothing module for gesture sequence coherence, and an
attention-based refinement module for enhanced realism. The model is trained on
our large-scale proprietary open-source dataset Allo-AVA. LBLM-AVA achieves
state-of-the-art performance in generating lifelike and contextually
appropriate gestures with a 30% reduction in Fr\'echet Gesture Distance (FGD),
and a 25% improvement in Fr\'echet Inception Distance compared to existing
approaches.
