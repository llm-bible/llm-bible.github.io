---
layout: publication
title: 'When Large Vision-language Models Meet Person Re-identification'
authors: Qizao Wang, Bin Li, Xiangyang Xue
conference: "Arxiv"
year: 2024
bibkey: wang2024when
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.18111'}
tags: ['Multimodal Models', 'Training Techniques', 'Tools']
---
Large Vision-Language Models (LVLMs) that incorporate visual models and Large
Language Models (LLMs) have achieved impressive results across various
cross-modal understanding and reasoning tasks. In recent years, person
re-identification (ReID) has also started to explore cross-modal semantics to
improve the accuracy of identity recognition. However, effectively utilizing
LVLMs for ReID remains an open challenge. While LVLMs operate under a
generative paradigm by predicting the next output word, ReID requires the
extraction of discriminative identity features to match pedestrians across
cameras. In this paper, we propose LVLM-ReID, a novel framework that harnesses
the strengths of LVLMs to promote ReID. Specifically, we employ instructions to
guide the LVLM in generating one pedestrian semantic token that encapsulates
key appearance semantics from the person image. This token is further refined
through our Semantic-Guided Interaction (SGI) module, establishing a reciprocal
interaction between the semantic token and visual tokens. Ultimately, the
reinforced semantic token serves as the pedestrian identity representation. Our
framework integrates the semantic understanding and generation capabilities of
LVLMs into end-to-end ReID training, allowing LVLMs to capture rich semantic
cues from pedestrian images during both training and inference. Our method
achieves competitive results on multiple benchmarks without additional
image-text annotations, demonstrating the potential of LVLM-generated semantics
to advance person ReID and offering a promising direction for future research.
