---
layout: publication
title: 'Is Less More? Exploring Token Condensation As Training-free Test-time Adaptation'
authors: Zixin Wang, Dong Gong, Sen Wang, Zi Huang, Yadan Luo
conference: "Arxiv"
year: 2024
bibkey: wang2024is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14729"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Contrastive Language-Image Pretraining (CLIP) excels at learning
generalizable image representations but often falls short in zero-shot
inference on certain downstream datasets. Test-time adaptation (TTA) mitigates
this issue by adjusting components like normalization layers or context
prompts, yet it typically requires large batch sizes and extensive
augmentations, leading to high computational costs. This raises a key question:
Can VLMs' performance drop in specific test cases be mitigated through
efficient, training-free approaches? To explore the solution, we investigate
token condensation (TC) techniques, originally designed to enhance vision
transformer efficiency by refining token usage during inference. We observe
that informative tokens improve visual-text alignment in VLMs like CLIP on
unseen datasets. However, existing TC methods often fail to maintain
in-distribution performance when reducing tokens, prompting us to ask: How can
we transform TC into an effective ``free-lunch'' adaptation strategy for VLMs?
To address this, we propose Token Condensation as Adaptation (TCA), a
training-free adaptation method that takes a step beyond standard TC. Rather
than passively discarding tokens, TCA condenses token representation by
introducing reservoir-based domain anchor tokens for information-preserving
token reduction and logits correction. TCA achieves up to a 21.4% performance
improvement over the strongest baseline on cross-dataset benchmark and the
CIFAR-100-Corrupted dataset while reducing GFLOPs by 12.2% to 48.9%, with
minimal hyperparameter dependency on both CLIP and SigLIP series.
