---
layout: publication
title: 'Doubly-universal Adversarial Perturbations: Deceiving Vision-language Models Across Both Images And Text With A Single Perturbation'
authors: Hee-seon Kim, Minbeom Kim, Changick Kim
conference: "Arxiv"
year: 2024
bibkey: kim2024doubly
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08108'}
tags: ['Attention Mechanism', 'Transformer', 'Security', 'Model Architecture', 'Multimodal Models']
---
Large Vision-Language Models (VLMs) have demonstrated remarkable performance
across multimodal tasks by integrating vision encoders with large language
models (LLMs). However, these models remain vulnerable to adversarial attacks.
Among such attacks, Universal Adversarial Perturbations (UAPs) are especially
powerful, as a single optimized perturbation can mislead the model across
various input images. In this work, we introduce a novel UAP specifically
designed for VLMs: the Doubly-Universal Adversarial Perturbation (Doubly-UAP),
capable of universally deceiving VLMs across both image and text inputs. To
successfully disrupt the vision encoder's fundamental process, we analyze the
core components of the attention mechanism. After identifying value vectors in
the middle-to-late layers as the most vulnerable, we optimize Doubly-UAP in a
label-free manner with a frozen model. Despite being developed as a black-box
to the LLM, Doubly-UAP achieves high attack success rates on VLMs, consistently
outperforming baseline methods across vision-language tasks. Extensive ablation
studies and analyses further demonstrate the robustness of Doubly-UAP and
provide insights into how it influences internal attention mechanisms.
