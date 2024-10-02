---
layout: publication
title: 'Don''t Sweep Your Learning Rate Under The Rug: A Closer Look At Cross-modal Transfer Of Pretrained Transformers'
authors: Rothermel Danielle, Li Margaret, Rocktäschel Tim, Foerster Jakob
conference: "Arxiv"
year: 2021
bibkey: rothermel2021sweep
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.12460"}
tags: ['Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
'Self-supervised pre-training of large-scale transformer models on text corpora followed by finetuning has achieved state-of-the-art on a number of natural language processing tasks. Recently, Lu et al. (2021, arXiv:2103.05247) claimed that frozen pretrained transformers (FPTs) match or outperform training from scratch as well as unfrozen (fine-tuned) pretrained transformers in a set of transfer tasks to other modalities. In our work, we find that this result is, in fact, an artifact of not tuning the learning rates. After carefully redesigning the empirical setup, we find that when tuning learning rates properly, pretrained transformers do outperform or match training from scratch in all of our tasks, but only as long as the entire model is finetuned. Thus, while transfer from pretrained language models to other modalities does indeed provide gains and hints at exciting possibilities for future work, properly tuning hyperparameters is important for arriving at robust findings.'
