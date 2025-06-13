---
layout: publication
title: 'Enhancing Transformers Through Conditioned Embedded Tokens'
authors: Hemanth Saratchandran, Simon Lucey
conference: "Arxiv"
year: 2025
bibkey: saratchandran2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12789"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Transformers have transformed modern machine learning, driving breakthroughs in computer vision, natural language processing, and robotics. At the core of their success lies the attention mechanism, which enables the modeling of global dependencies among input tokens. However, we reveal that the attention block in transformers suffers from inherent ill-conditioning, which hampers gradient-based optimization and leads to inefficient training. To address this, we develop a theoretical framework that establishes a direct relationship between the conditioning of the attention block and that of the embedded tokenized data. Building on this insight, we introduce conditioned embedded tokens, a method that systematically modifies the embedded tokens to improve the conditioning of the attention mechanism. Our analysis demonstrates that this approach significantly mitigates ill-conditioning, leading to more stable and efficient training. We validate our methodology across various transformer architectures, achieving consistent improvements in image classification, object detection, instance segmentation, and natural language processing, highlighting its broad applicability and effectiveness.
