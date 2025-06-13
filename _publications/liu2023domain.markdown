---
layout: publication
title: 'DAP: Domain-aware Prompt Learning For Vision-and-language Navigation'
authors: Ting Liu, Yue Hu, Wansen Wu, Youkai Wang, Kai Xu, Quanjun Yin
conference: "Arxiv"
year: 2023
bibkey: liu2023domain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17812"}
tags: ['Prompting', 'Multimodal Models', 'Agentic', 'Tools']
---
Following language instructions to navigate in unseen environments is a
challenging task for autonomous embodied agents. With strong representation
capabilities, pretrained vision-and-language models are widely used in VLN.
However, most of them are trained on web-crawled general-purpose datasets,
which incurs a considerable domain gap when used for VLN tasks. To address the
problem, we propose a novel and model-agnostic domain-aware prompt learning
(DAP) framework. For equipping the pretrained models with specific object-level
and scene-level cross-modal alignment in VLN tasks, DAP applies a low-cost
prompt tuning paradigm to learn soft visual prompts for extracting in-domain
image semantics. Specifically, we first generate a set of in-domain image-text
pairs with the help of the CLIP model. Then we introduce soft visual prompts in
the input space of the visual encoder in a pretrained model. DAP injects
in-domain visual knowledge into the visual encoder of the pretrained model in
an efficient way. Experimental results on both R2R and REVERIE show the
superiority of DAP compared to existing state-of-the-art methods.
