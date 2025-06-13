---
layout: publication
title: 'Approximated Prompt Tuning For Vision-language Pre-trained Models'
authors: Qiong Wu, Shubin Huang, Yiyi Zhou, Pingyang Dai, Annan Shu, Guannan Jiang, Rongrong Ji
conference: "Arxiv"
year: 2023
bibkey: wu2023approximated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.15706"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Prompting', 'Pre-Training', 'Attention Mechanism']
---
Prompt tuning is a parameter-efficient way to deploy large-scale pre-trained
models to downstream tasks by adding task-specific tokens. In terms of
vision-language pre-trained (VLP) models, prompt tuning often requires a large
number of learnable tokens to bridge the gap between the pre-training and
downstream tasks, which greatly exacerbates the already high computational
overhead. In this paper, we revisit the principle of prompt tuning for
Transformer-based VLP models, and reveal that the impact of soft prompt tokens
can be actually approximated via independent information diffusion steps,
thereby avoiding the expensive global attention modeling and reducing the
computational complexity to a large extent. Based on this finding, we propose a
novel Approximated Prompt Tuning (APT) approach towards efficient VL transfer
learning. To validate APT, we apply it to two representative VLP models, namely
ViLT and METER, and conduct extensive experiments on a bunch of downstream
tasks. Meanwhile, the generalization of APT is also validated on CLIP for image
classification and StableDiffusion for text-to-image generation. The
experimental results not only show the superior performance gains and
computation efficiency of APT against the conventional prompt tuning methods,
e.g., +7.01% accuracy and -82.30% additional computation overhead on METER, but
also confirm its merits over other parameter-efficient transfer learning
approaches.
