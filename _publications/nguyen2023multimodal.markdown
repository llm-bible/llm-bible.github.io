---
layout: publication
title: 'Openvivqa: Task, Dataset, And Multimodal Fusion Models For Visual Question
  Answering In Vietnamese'
authors: Nghia Hieu Nguyen, Duong T. D. Vo, Kiet Van Nguyen, Ngan Luu-thuy Nguyen
conference: Arxiv
year: 2023
citations: 15
bibkey: nguyen2023multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.04183'}]
tags: [Transformer, RAG, Fine-Tuning, Applications, Multimodal Models]
---
In recent years, visual question answering (VQA) has attracted attention from
the research community because of its highly potential applications (such as
virtual assistance on intelligent cars, assistant devices for blind people, or
information retrieval from document images using natural language as queries)
and challenge. The VQA task requires methods that have the ability to fuse the
information from questions and images to produce appropriate answers. Neural
visual question answering models have achieved tremendous growth on large-scale
datasets which are mostly for resource-rich languages such as English. However,
available datasets narrow the VQA task as the answers selection task or answer
classification task. We argue that this form of VQA is far from human ability
and eliminates the challenge of the answering aspect in the VQA task by just
selecting answers rather than generating them. In this paper, we introduce the
OpenViVQA (Open-domain Vietnamese Visual Question Answering) dataset, the first
large-scale dataset for VQA with open-ended answers in Vietnamese, consists of
11,000+ images associated with 37,000+ question-answer pairs (QAs). Moreover,
we proposed FST, QuMLAG, and MLPAG which fuse information from images and
answers, then use these fused features to construct answers as humans
iteratively. Our proposed methods achieve results that are competitive with
SOTA models such as SAAA, MCAN, LORA, and M4C. The dataset is available to
encourage the research community to develop more generalized algorithms
including transformers for low-resource languages such as Vietnamese.