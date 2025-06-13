---
layout: publication
title: 'Geopix: Multi-modal Large Language Model For Pixel-level Image Understanding In Remote Sensing'
authors: Ruizhe Ou, Yuan Hu, Fan Zhang, Jiaxin Chen, Yu Liu
conference: "Arxiv"
year: 2025
bibkey: ou2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06828"}
tags: ['Applications', 'Training Techniques', 'Efficiency and Optimization', 'Language Modeling']
---
Multi-modal large language models (MLLMs) have achieved remarkable success in
image- and region-level remote sensing (RS) image understanding tasks, such as
image captioning, visual question answering, and visual grounding. However,
existing RS MLLMs lack the pixel-level dialogue capability, which involves
responding to user instructions with segmentation masks for specific instances.
In this paper, we propose GeoPix, a RS MLLM that extends image understanding
capabilities to the pixel level. This is achieved by equipping the MLLM with a
mask predictor, which transforms visual features from the vision encoder into
masks conditioned on the LLM's segmentation token embeddings. To facilitate the
segmentation of multi-scale objects in RS imagery, a class-wise learnable
memory module is integrated into the mask predictor to capture and store
class-wise geo-context at the instance level across the entire dataset. In
addition, to address the absence of large-scale datasets for training
pixel-level RS MLLMs, we construct the GeoPixInstruct dataset, comprising
65,463 images and 140,412 instances, with each instance annotated with text
descriptions, bounding boxes, and masks. Furthermore, we develop a two-stage
training strategy to balance the distinct requirements of text generation and
masks prediction in multi-modal multi-task optimization. Extensive experiments
verify the effectiveness and superiority of GeoPix in pixel-level segmentation
tasks, while also maintaining competitive performance in image- and
region-level benchmarks.
