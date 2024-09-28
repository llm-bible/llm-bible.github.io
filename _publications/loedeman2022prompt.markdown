---
layout: publication
title: Prompt Generation Networks for Input-Space Adaptation of Frozen Vision Transformers
authors: Loedeman Jochem, Stol Maarten C., Han Tengda, Asano Yuki M.
conference: "Arxiv"
year: 2022
bibkey: loedeman2022prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06466"}
tags: ['ARXIV', 'Model Architecture', 'NLP', 'Prompt', 'Security', 'Tools', 'Transformer']
---
With the introduction of the transformer architecture in computer vision increasing model scale has been demonstrated as a clear path to achieving performance and robustness gains. However with model parameter counts reaching the billions classical finetuning approaches are becoming increasingly limiting and even unfeasible when models become hosted as inference APIs as in NLP. Visual input-prompt learning an adaptation technique in which additional inputs in visual (RGB) space are learned has emerged as a potential solution for adapting frozen and cloud-hosted models requiring neither access to the forward pass nor post-processing. Yet so far these constraints have deteriorated adaptation performances significantly. To this end we propose the Prompt Generation Network (PGN) that generates a different prompt for every data point which is then used to adapt a frozen pretrained vision model to a target task. We show that the PGN effectively adapts pretrained models to various new datasets It surpasses previous methods by a large margin on 12/12 datasets and even outperforms full-finetuning on 5/12 while requiring 100x fewer parameters. Lastly we introduce the prompt inversion trick with which PGNs can be efficiently trained in a latent space but deployed in RGB input space for inference.
