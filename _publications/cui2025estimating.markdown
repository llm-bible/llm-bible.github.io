---
layout: publication
title: 'Estimating Commonsense Plausibility Through Semantic Shifts'
authors: Wanqing Cui, Keping Bi, Jiafeng Guo, Xueqi Cheng
conference: "Arxiv"
year: 2025
bibkey: cui2025estimating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13464"}
tags: ['Multimodal Models', 'Training Techniques', 'Pre-Training', 'Tools']
---
Commonsense plausibility estimation is critical for evaluating language
models (LMs), yet existing generative approaches--reliant on likelihoods or
verbalized judgments--struggle with fine-grained discrimination. In this paper,
we propose ComPaSS, a novel discriminative framework that quantifies
commonsense plausibility by measuring semantic shifts when augmenting sentences
with commonsense-related information. Plausible augmentations induce minimal
shifts in semantics, while implausible ones result in substantial deviations.
Evaluations on two types of fine-grained commonsense plausibility estimation
tasks across different backbones, including LLMs and vision-language models
(VLMs), show that ComPaSS consistently outperforms baselines. It demonstrates
the advantage of discriminative approaches over generative methods in
fine-grained commonsense plausibility evaluation. Experiments also show that
(1) VLMs yield superior performance to LMs, when integrated with ComPaSS, on
vision-grounded commonsense tasks. (2) contrastive pre-training sharpens
backbone models' ability to capture semantic nuances, thereby further enhancing
ComPaSS.
