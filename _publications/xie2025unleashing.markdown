---
layout: publication
title: 'Unleashing The Potential Of Large Language Models For Text-to-image Generation Through Autoregressive Representation Alignment'
authors: Xing Xie, Jiawei Liu, Ziyue Lin, Huijie Fan, Zhi Han, Yandong Tang, Liangqiong Qu
conference: "Arxiv"
year: 2025
bibkey: xie2025unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07334"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Tools', 'Language Modeling', 'Distillation', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
We present Autoregressive Representation Alignment (ARRA), a new training
framework that unlocks global-coherent text-to-image generation in
autoregressive LLMs without architectural changes. Unlike prior work that
requires complex architectural redesigns, ARRA aligns LLM hidden states with
visual representations from external visual foundational models via a global
visual alignment loss and a hybrid token, <HYBNEXT>. This token enforces dual
constraints: local next-token prediction and global semantic distillation,
enabling LLMs to implicitly learn spatial and contextual coherence while
retaining their original autoregressive paradigm. Extensive experiments
validate ARRA's plug-and-play versatility. When training from
text-generation-only LLMs or random initialization, ARRA reduces FID by 25.5%
(MIMIC-CXR), 8.8% (DeepEyeNet), and 7.5% (ImageNet) for advanced autoregressive
LLMs like Chameleon and LlamaGen, all without framework modifications. For
domain adaption, ARRA aligns general-purpose LLMs with specialized models
(e.g., BioMedCLIP), achieving an 18.6% FID reduction over direct fine-tuning on
medical imaging (MIMIC-CXR). By demonstrating that training objective redesign
-- not just architectural innovation -- can resolve cross-modal global
coherence challenges, ARRA offers a complementary paradigm for advancing
autoregressive models. Code and models will be released to advance
autoregressive image generation.
