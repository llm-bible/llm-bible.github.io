---
layout: publication
title: 'Object-attribute Binding In Text-to-image Generation: Evaluation And Control'
authors: Maria Mihaela Trusca, Wolf Nuyts, Jonathan Thomm, Robert Honig, Thomas Hofmann, Tinne Tuytelaars, Marie-francine Moens
conference: "Arxiv"
year: 2024
bibkey: trusca2024object
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.13766'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Merging', 'Prompting', 'Multimodal Models', 'Pretraining Methods']
---
Current diffusion models create photorealistic images given a text prompt as
input but struggle to correctly bind attributes mentioned in the text to the
right objects in the image. This is evidenced by our novel image-graph
alignment model called EPViT (Edge Prediction Vision Transformer) for the
evaluation of image-text alignment. To alleviate the above problem, we propose
focused cross-attention (FCA) that controls the visual attention maps by
syntactic constraints found in the input sentence. Additionally, the syntax
structure of the prompt helps to disentangle the multimodal CLIP embeddings
that are commonly used in T2I generation. The resulting DisCLIP embeddings and
FCA are easily integrated in state-of-the-art diffusion models without
additional training of these models. We show substantial improvements in T2I
generation and especially its attribute-object binding on several
datasets.\footnote\{Code and data will be made available upon acceptance.
