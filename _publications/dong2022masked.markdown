---
layout: publication
title: 'Maskclip: Masked Self-distillation Advances Contrastive Language-image Pretraining'
authors: Xiaoyi Dong et al.
conference: Arxiv
year: 2022
citations: 79
bibkey: dong2022masked
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.12262'}, {name: Code,
    url: 'https://github.com/LightDXY/MaskCLIP'}]
tags: [Distillation, Multimodal Models, Pre-Training]
---
This paper presents a simple yet effective framework MaskCLIP, which
incorporates a newly proposed masked self-distillation into contrastive
language-image pretraining. The core idea of masked self-distillation is to
distill representation from a full image to the representation predicted from a
masked image. Such incorporation enjoys two vital benefits. First, masked
self-distillation targets local patch representation learning, which is
complementary to vision-language contrastive focusing on text-related
representation. Second, masked self-distillation is also consistent with
vision-language contrastive from the perspective of training objective as both
utilize the visual encoder for feature aligning, and thus is able to learn
local semantics getting indirect supervision from the language. We provide
specially designed experiments with a comprehensive analysis to validate the
two benefits. Symmetrically, we also introduce the local semantic supervision
into the text branch, which further improves the pretraining performance. With
extensive experiments, we show that MaskCLIP, when applied to various
challenging downstream tasks, achieves superior results in linear probing,
finetuning, and zero-shot performance with the guidance of the language
encoder. Code will be release at https://github.com/LightDXY/MaskCLIP.