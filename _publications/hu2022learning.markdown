---
layout: publication
title: In-context Learning For Few-shot Dialogue State Tracking
authors: Yushi Hu et al.
conference: Arxiv
year: 2022
citations: 21
bibkey: hu2022learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.08568'}]
tags: [Few-Shot, In-Context Learning, Prompting]
---
Collecting and annotating task-oriented dialogues is time-consuming and
costly; thus, zero and few shot learning could greatly benefit dialogue state
tracking (DST). In this work, we propose an in-context learning (ICL) framework
for zero-shot and few-shot learning DST, where a large pre-trained language
model (LM) takes a test instance and a few exemplars as input, and directly
decodes the dialogue state without any parameter updates. To better leverage a
tabular domain description in the LM prompt, we reformulate DST into a
text-to-SQL problem. We also propose a novel approach to retrieve annotated
dialogues as exemplars. Empirical results on MultiWOZ show that our method
IC-DST substantially outperforms previous fine-tuned state-of-the-art models in
few-shot settings. In addition, we test IC-DST in zero-shot settings, in which
the model only takes a fixed task instruction as input, finding that it
outperforms previous zero-shot methods by a large margin.