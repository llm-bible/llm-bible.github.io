---
layout: publication
title: 'Clip-adapter: Better Vision-language Models With Feature Adapters'
authors: Peng Gao et al.
conference: Arxiv
year: 2021
citations: 368
bibkey: gao2021clip
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.04544'}, {name: Code,
    url: 'https://github.com/gaopengcuhk/CLIP-Adapter'}]
tags: [Pre-Training, Few-Shot, Fine-Tuning, Multimodal Models, Prompting]
---
Large-scale contrastive vision-language pre-training has shown significant
progress in visual representation learning. Unlike traditional visual systems
trained by a fixed set of discrete labels, a new paradigm was introduced in
\cite\{radford2021learning\} to directly learn to align images with raw texts in
an open-vocabulary setting. On downstream tasks, a carefully chosen text prompt
is employed to make zero-shot predictions.~To avoid non-trivial prompt
engineering, context optimization \cite\{zhou2021coop\} has been proposed to
learn continuous vectors as task-specific prompts with few-shot training
examples.~In this paper, we show that there is an alternative path to achieve
better vision-language models other than prompt tuning.~While prompt tuning is
for the textual inputs, we propose CLIP-Adapter to conduct fine-tuning with
feature adapters on either visual or language branch. Specifically,
CLIP-Adapter adopts an additional bottleneck layer to learn new features and
performs residual-style feature blending with the original pre-trained
features.~As a consequence, CLIP-Adapter is able to outperform context
optimization while maintains a simple design. Experiments and extensive
ablation studies on various visual classification tasks demonstrate the
effectiveness of our approach. Code is released at t
https://github.com/gaopengcuhk/CLIP-Adapter.