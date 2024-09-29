---
layout: publication
title: 'An Adversarial Example For Direct Logit Attribution: Memory Management In Gelu-4l'
authors: Dao James, Lau Yeu-tong, Rager Can, Janiak Jett
conference: "Arxiv"
year: 2023
bibkey: dao2023adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07325"}
tags: ['Attention Mechanism', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Security', 'Transformer']
---
How do language models deal with the limited bandwidth of the residual stream Prior work has suggested that some attention heads and MLP layers may perform a memory management role. That is clearing residual stream directions set by earlier layers by reading in information and writing out the negative version. In this work we present concrete evidence for this phenomenon in a 4-layer transformer. We identify several heads in layer 2 that consistently remove the output of a single layer 0 head. We then verify that this erasure causally depends on the original written direction. We further demonstrate that direct logit attribution (DLA) suggests that writing and erasing heads directly contribute to predictions when in fact their effects cancel out. Then we present adversarial prompts for which this effect is particularly salient. These findings reveal that memory management can make DLA results misleading. Accordingly we make concrete recommendations for circuit analysis to prevent interpretability illusions.
