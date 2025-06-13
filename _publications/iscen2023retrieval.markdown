---
layout: publication
title: 'Retrieval-enhanced Contrastive Vision-text Models'
authors: Ahmet Iscen, Mathilde Caron, Alireza Fathi, Cordelia Schmid
conference: "Arxiv"
year: 2023
bibkey: iscen2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.07196"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Merging', 'Pretraining Methods', 'Transformer', 'Pre-Training']
---
Contrastive image-text models such as CLIP form the building blocks of many
state-of-the-art systems. While they excel at recognizing common generic
concepts, they still struggle on fine-grained entities which are rare, or even
absent from the pre-training dataset. Hence, a key ingredient to their success
has been the use of large-scale curated pre-training data aiming at expanding
the set of concepts that they can memorize during the pre-training stage. In
this work, we explore an alternative to encoding fine-grained knowledge
directly into the model's parameters: we instead train the model to retrieve
this knowledge from an external memory. Specifically, we propose to equip
existing vision-text models with the ability to refine their embedding with
cross-modal retrieved information from a memory at inference time, which
greatly improves their zero-shot predictions. Remarkably, we show that this can
be done with a light-weight, single-layer, fusion transformer on top of a
frozen CLIP. Our experiments validate that our retrieval-enhanced contrastive
(RECO) training improves CLIP performance substantially on several challenging
fine-grained tasks: for example +10.9 on Stanford Cars, +10.2 on CUB-2011 and
+7.3 on the recent OVEN benchmark, where we even outperform the fine-tuned
models on unseen classes.
