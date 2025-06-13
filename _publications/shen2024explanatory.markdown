---
layout: publication
title: 'Explanatory Instructions: Towards Unified Vision Tasks Understanding And Zero-shot Generalization'
authors: Yang Shen, Xiu-shen Wei, Yifan Sun, Yuxin Song, Tao Yuan, Jian Jin, Heyang Xu, Yazhou Yao, Errui Ding
conference: "Arxiv"
year: 2024
bibkey: shen2024explanatory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18525"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Transformer', 'Pre-Training']
---
Computer Vision (CV) has yet to fully achieve the zero-shot task generalization observed in Natural Language Processing (NLP), despite following many of the milestones established in NLP, such as large transformer models, extensive pre-training, and the auto-regression paradigm, among others. In this paper, we explore the idea that CV adopts discrete and terminological task definitions (\eg, ``image segmentation''), which may be a key barrier to zero-shot task generalization. Our hypothesis is that without truly understanding previously-seen tasks--due to these terminological definitions--deep models struggle to generalize to novel tasks. To verify this, we introduce Explanatory Instructions, which provide an intuitive way to define CV task objectives through detailed linguistic transformations from input images to outputs. We create a large-scale dataset comprising 12 million ``image input \\(\to\\) explanatory instruction \\(\to\\) output'' triplets, and train an auto-regressive-based vision-language model (AR-based VLM) that takes both images and explanatory instructions as input. By learning to follow these instructions, the AR-based VLM achieves instruction-level zero-shot capabilities for previously-seen tasks and demonstrates strong zero-shot generalization for unseen CV tasks. Code and dataset will be openly available on our GitHub repository.
