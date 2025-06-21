---
layout: publication
title: Unsupervised Vision-and-language Pre-training Without Parallel Images And Captions
authors: Liunian Harold Li et al.
conference: Arxiv
year: 2020
citations: 15
bibkey: li2020unsupervised
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12831'}]
tags: [Pre-Training, Multimodal Models]
---
Pre-trained contextual vision-and-language (V&L) models have achieved
impressive performance on various benchmarks. However, existing models require
a large amount of parallel image-caption data for pre-training. Such data are
costly to collect and require cumbersome curation. Inspired by unsupervised
machine translation, we investigate if a strong V&L representation model can be
learned through unsupervised pre-training without image-caption corpora. In
particular, we propose to conduct ``mask-and-predict'' pre-training on
text-only and image-only corpora and introduce the object tags detected by an
object recognition model as anchor points to bridge two modalities. We find
that such a simple approach achieves performance close to a model pre-trained
with aligned data, on four English V&L benchmarks. Our work challenges the
widely held notion that aligned data is necessary for V&L pre-training, while
significantly reducing the amount of supervision needed for V&L models.