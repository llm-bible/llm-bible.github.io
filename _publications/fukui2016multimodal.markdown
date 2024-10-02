---
layout: publication
title: 'Multimodal Compact Bilinear Pooling For Visual Question Answering And Visual Grounding'
authors: Fukui Akira, Park Dong Huk, Yang Daylen, Rohrbach Anna, Darrell Trevor, Rohrbach Marcus
conference: "Arxiv"
year: 2016
bibkey: fukui2016multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1606.01847"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Multimodal Models']
---
Modeling textual or visual information with vector representations trained from large language or visual datasets has been successfully explored in recent years. However, tasks such as visual question answering require combining these vector representations with each other. Approaches to multimodal pooling include element-wise product or sum, as well as concatenation of the visual and textual representations. We hypothesize that these methods are not as expressive as an outer product of the visual and textual vectors. As the outer product is typically infeasible due to its high dimensionality, we instead propose utilizing Multimodal Compact Bilinear pooling (MCB) to efficiently and expressively combine multimodal features. We extensively evaluate MCB on the visual question answering and grounding tasks. We consistently show the benefit of MCB over ablations without MCB. For visual question answering, we present an architecture which uses MCB twice, once for predicting attention over spatial features and again to combine the attended representation with the question representation. This model outperforms the state-of-the-art on the Visual7W dataset and the VQA challenge.
