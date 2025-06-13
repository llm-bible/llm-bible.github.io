---
layout: publication
title: 'Gazeclip: Enhancing Gaze Estimation Through Text-guided Multimodal Learning'
authors: Jun Wang, Hao Ruan, Liangjian Wen, Yong Dai, Mingjie Wang
conference: "Arxiv"
year: 2023
bibkey: wang2023enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2401.00260'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Multimodal Models', 'Pre-Training']
---
Visual gaze estimation, with its wide-ranging application scenarios, has
garnered increasing attention within the research community. Although existing
approaches infer gaze solely from image signals, recent advances in
visual-language collaboration have demonstrated that the integration of
linguistic information can significantly enhance performance across various
visual tasks. Leveraging the remarkable transferability of large-scale
Contrastive Language-Image Pre-training (CLIP) models, we address the open and
urgent question of how to effectively apply linguistic cues to gaze estimation.
In this work, we propose GazeCLIP, a novel gaze estimation framework that
deeply explores text-face collaboration. Specifically, we introduce a
meticulously designed linguistic description generator to produce text signals
enriched with coarse directional cues. Furthermore, we present a CLIP-based
backbone adept at characterizing text-face pairs for gaze estimation,
complemented by a fine-grained multimodal fusion module that models the
intricate interrelationships between heterogeneous inputs. Extensive
experiments on three challenging datasets demonstrate the superiority of
GazeCLIP, which achieves state-of-the-art accuracy. Our findings underscore the
potential of using visual-language collaboration to advance gaze estimation and
open new avenues for future research in multimodal learning for visual tasks.
The implementation code and the pre-trained model will be made publicly
available.
