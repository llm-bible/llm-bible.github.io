---
layout: publication
title: 'Protoclip: Prototypical Contrastive Language Image Pretraining'
authors: Delong Chen et al.
conference: Arxiv
year: 2022
citations: 40
bibkey: chen2022prototypical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.10996'}, {name: Code,
    url: 'https://github.com/megvii-research/protoclip'}]
tags: [Efficiency and Optimization, Reinforcement Learning, Model Architecture]
---
Contrastive Language Image Pretraining (CLIP) has received widespread
attention, since its learned representations can be transferred well to various
downstream tasks. During the training process of the CLIP model, the InfoNCE
objective aligns positive image-text pairs and separates negative ones. We show
an underlying representation grouping effect during this process: the InfoNCE
objective indirectly groups semantically similar representations together via
randomly emerged within-modal anchors. Based on this understanding, in this
paper, Prototypical Contrastive Language Image Pretraining (ProtoCLIP) is
introduced to enhance such grouping by boosting its efficiency and increasing
its robustness against the modality gap. Specifically, ProtoCLIP sets up
prototype-level discrimination between image and text spaces, which efficiently
transfers higher-level structural knowledge. Further, Prototypical Back
Translation (PBT) is proposed to decouple representation grouping from
representation alignment, resulting in effective learning of meaningful
representations under large modality gap. The PBT also enables us to introduce
additional external teachers with richer prior language knowledge. ProtoCLIP is
trained with an online episodic training strategy, which makes it can be scaled
up to unlimited amounts of data. We train our ProtoCLIP on Conceptual Captions
and achieved an +5.81% ImageNet linear probing improvement and an +2.01%
ImageNet zero-shot classification improvement. On the larger YFCC-15M dataset,
ProtoCLIP matches the performance of CLIP with 33% of training time. Codes are
available at https://github.com/megvii-research/protoclip.