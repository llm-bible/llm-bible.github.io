---
layout: publication
title: 'SOAT: A Scene- And Object-aware Transformer For Vision-and-language Navigation'
authors: Abhinav Moudgil, Arjun Majumdar, Harsh Agrawal, Stefan Lee, Dhruv Batra
conference: Arxiv
year: 2021
citations: 21
bibkey: moudgil2021scene
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.14143'}]
tags: [Transformer, Reinforcement Learning, Agentic]
---
Natural language instructions for visual navigation often use scene
descriptions (e.g., "bedroom") and object references (e.g., "green chairs") to
provide a breadcrumb trail to a goal location. This work presents a
transformer-based vision-and-language navigation (VLN) agent that uses two
different visual encoders -- a scene classification network and an object
detector -- which produce features that match these two distinct types of
visual cues. In our method, scene features contribute high-level contextual
information that supports object-level processing. With this design, our model
is able to use vision-and-language pretraining (i.e., learning the alignment
between images and text from large-scale web data) to substantially improve
performance on the Room-to-Room (R2R) and Room-Across-Room (RxR) benchmarks.
Specifically, our approach leads to improvements of 1.8% absolute in SPL on R2R
and 3.7% absolute in SR on RxR. Our analysis reveals even larger gains for
navigation instructions that contain six or more object references, which
further suggests that our approach is better able to use object features and
align them to references in the instructions.