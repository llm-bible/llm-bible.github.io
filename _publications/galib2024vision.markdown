---
layout: publication
title: 'H2ovl-mississippi Vision Language Models Technical Report'
authors: Shaikat Galib, Shanshan Wang, Guanshuo Xu, Pascal Pfeiffer, Ryan Chesler, Mark Landry, Sri Satish Ambati
conference: "Arxiv"
year: 2024
bibkey: galib2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13611"}
tags: ['Multimodal Models', 'Applications']
---
Smaller vision-language models (VLMs) are becoming increasingly important for
privacy-focused, on-device applications due to their ability to run efficiently
on consumer hardware for processing enterprise commercial documents and images.
These models require strong language understanding and visual capabilities to
enhance human-machine interaction. To address this need, we present
H2OVL-Mississippi, a pair of small VLMs trained on 37 million image-text pairs
using 240 hours of compute on 8 x H100 GPUs. H2OVL-Mississippi-0.8B is a tiny
model with 0.8 billion parameters that specializes in text recognition,
achieving state of the art performance on the Text Recognition portion of
OCRBench and surpassing much larger models in this area. Additionally, we are
releasing H2OVL-Mississippi-2B, a 2 billion parameter model for general use
cases, exhibiting highly competitive metrics across various academic
benchmarks. Both models build upon our prior work with H2O-Danube language
models, extending their capabilities into the visual domain. We release them
under the Apache 2.0 license, making VLMs accessible to everyone, democratizing
document AI and visual LLMs.
