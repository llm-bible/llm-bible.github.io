---
layout: publication
title: 'Siglip 2: Multilingual Vision-language Encoders With Improved Semantic Understanding, Localization, And Dense Features'
authors: Michael Tschannen, Alexey Gritsenko, Xiao Wang, Muhammad Ferjad Naeem, Ibrahim Alabdulmohsin, Nikhil Parthasarathy, Talfan Evans, Lucas Beyer, Ye Xia, Basil Mustafa, Olivier Hénaff, Jeremiah Harmsen, Andreas Steiner, Xiaohua Zhai
conference: "Arxiv"
year: 2025
bibkey: tschannen2025siglip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14786"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fairness', 'Multimodal Models', 'Reinforcement Learning', 'Distillation', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods']
---
We introduce SigLIP 2, a family of new multilingual vision-language encoders
that build on the success of the original SigLIP. In this second iteration, we
extend the original image-text training objective with several prior,
independently developed techniques into a unified recipe -- this includes
captioning-based pretraining, self-supervised losses (self-distillation, masked
prediction) and online data curation. With these changes, SigLIP 2 models
outperform their SigLIP counterparts at all model scales in core capabilities,
including zero-shot classification, image-text retrieval, and transfer
performance when extracting visual representations for Vision-Language Models
(VLMs). Furthermore, the new training recipe leads to significant improvements
on localization and dense prediction tasks. We also train variants which
support multiple resolutions and preserve the input's native aspect ratio.
Finally, we train on a more diverse data-mixture that includes de-biasing
techniques, leading to much better multilingual understanding and improved
fairness. To allow users to trade off inference cost with performance, we
release model checkpoints at four sizes: ViT-B (86M), L (303M), So400m (400M),
and g (1B).
