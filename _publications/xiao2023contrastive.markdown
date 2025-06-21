---
layout: publication
title: Contrastive Video Question Answering Via Video Graph Transformer
authors: Junbin Xiao et al.
conference: Arxiv
year: 2023
citations: 20
bibkey: xiao2023contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.13668'}, {name: Code,
    url: 'https://github.com/doc-doc/CoVGT'}]
tags: [Transformer, Multimodal Models]
---
We propose to perform video question answering (VideoQA) in a Contrastive
manner via a Video Graph Transformer model (CoVGT). CoVGT's uniqueness and
superiority are three-fold: 1) It proposes a dynamic graph transformer module
which encodes video by explicitly capturing the visual objects, their relations
and dynamics, for complex spatio-temporal reasoning. 2) It designs separate
video and text transformers for contrastive learning between the video and text
to perform QA, instead of multi-modal transformer for answer classification.
Fine-grained video-text communication is done by additional cross-modal
interaction modules. 3) It is optimized by the joint fully- and self-supervised
contrastive objectives between the correct and incorrect answers, as well as
the relevant and irrelevant questions respectively. With superior video
encoding and QA solution, we show that CoVGT can achieve much better
performances than previous arts on video reasoning tasks. Its performances even
surpass those models that are pretrained with millions of external data. We
further show that CoVGT can also benefit from cross-modal pretraining, yet with
orders of magnitude smaller data. The results demonstrate the effectiveness and
superiority of CoVGT, and additionally reveal its potential for more
data-efficient pretraining. We hope our success can advance VideoQA beyond
coarse recognition/description towards fine-grained relation reasoning of video
contents. Our code is available at https://github.com/doc-doc/CoVGT.