---
layout: publication
title: 'Moda: Modulation Adapter For Fine-grained Visual Grounding In Instructional Mllms'
authors: Wayner Barrios, Andrés Villa, Juan León Alcázar, Souyoung Jin, Bernard Ghanem
conference: "Arxiv"
year: 2025
bibkey: barrios2025modulation
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01850'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Training Techniques', 'GPT', 'Multimodal Models', 'Pretraining Methods']
---
Recently, Multimodal Large Language Models (MLLMs) have demonstrated impressive performance on instruction-following tasks by integrating pretrained visual encoders with large language models (LLMs). However, existing approaches often struggle to ground fine-grained visual concepts in complex scenes. In this paper, we propose MoDA (Modulation Adapter), a lightweight yet effective module designed to refine pre-aligned visual features through instruction-guided modulation. Our approach follows the standard LLaVA training protocol, consisting of a two-stage process: (1) aligning image features to the LLMs input space via a frozen vision encoder and adapter layers, and (2) refining those features using the MoDA adapter during the instructional tuning stage. MoDA employs a Transformer-based cross-attention mechanism to generate a modulation mask over the aligned visual tokens, thereby emphasizing semantically relevant embedding dimensions based on the language instruction. The modulated features are then passed to the LLM for autoregressive language generation. Our experimental evaluation shows that MoDA improves visual grounding and generates more contextually appropriate responses, demonstrating its effectiveness as a general-purpose enhancement for image-based MLLMs.
