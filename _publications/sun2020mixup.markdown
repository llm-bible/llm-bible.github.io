---
layout: publication
title: 'Mixup-transformer: Dynamic Data Augmentation For NLP Tasks'
authors: Lichao Sun et al.
conference: Arxiv
year: 2020
citations: 60
bibkey: sun2020mixup
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.02394'}]
tags: [Transformer, BERT, Pre-Training]
---
Mixup is the latest data augmentation technique that linearly interpolates
input examples and the corresponding labels. It has shown strong effectiveness
in image classification by interpolating images at the pixel level. Inspired by
this line of research, in this paper, we explore i) how to apply mixup to
natural language processing tasks since text data can hardly be mixed in the
raw format; ii) if mixup is still effective in transformer-based learning
models, e.g., BERT. To achieve the goal, we incorporate mixup to
transformer-based pre-trained architecture, named "mixup-transformer", for a
wide range of NLP tasks while keeping the whole end-to-end training system. We
evaluate the proposed framework by running extensive experiments on the GLUE
benchmark. Furthermore, we also examine the performance of mixup-transformer in
low-resource scenarios by reducing the training data with a certain ratio. Our
studies show that mixup is a domain-independent data augmentation technique to
pre-trained language models, resulting in significant performance improvement
for transformer-based models.