---
layout: publication
title: 'ROSITA: Enhancing Vision-and-language Semantic Alignments Via Cross- And Intra-modal
  Knowledge Integration'
authors: Yuhao Cui et al.
conference: Arxiv
year: 2021
citations: 32
bibkey: cui2021enhancing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.07073'}]
tags: [Multimodal Models]
---
Vision-and-language pretraining (VLP) aims to learn generic multimodal
representations from massive image-text pairs. While various successful
attempts have been proposed, learning fine-grained semantic alignments between
image-text pairs plays a key role in their approaches. Nevertheless, most
existing VLP approaches have not fully utilized the intrinsic knowledge within
the image-text pairs, which limits the effectiveness of the learned alignments
and further restricts the performance of their models. To this end, we
introduce a new VLP method called ROSITA, which integrates the cross- and
intra-modal knowledge in a unified scene graph to enhance the semantic
alignments. Specifically, we introduce a novel structural knowledge masking
(SKM) strategy to use the scene graph structure as a priori to perform masked
language (region) modeling, which enhances the semantic alignments by
eliminating the interference information within and across modalities.
Extensive ablation studies and comprehensive analysis verifies the
effectiveness of ROSITA in semantic alignments. Pretrained with both in-domain
and out-of-domain datasets, ROSITA significantly outperforms existing
state-of-the-art VLP methods on three typical vision-and-language tasks over
six benchmark datasets.