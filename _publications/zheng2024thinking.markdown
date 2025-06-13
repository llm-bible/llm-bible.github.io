---
layout: publication
title: 'Thinking Before Looking: Improving Multimodal LLM Reasoning Via Mitigating Visual Hallucination'
authors: Haojie Zheng, Tianyang Xu, Hanchi Sun, Shu Pu, Ruoxi Chen, Lichao Sun
conference: "Arxiv"
year: 2024
bibkey: zheng2024thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.12591"}
  - {name: "Code", url: "https://github.com/Terry-Xu-666/visual_inference_chain"}
tags: ['Ethics and Bias', 'Multimodal Models', 'Has Code', 'Tools']
---
Multimodal large language models (MLLMs) have advanced the integration of
visual and linguistic modalities, establishing themselves as the dominant
paradigm for visual-language tasks. Current approaches like chain of thought
(CoT) reasoning have augmented the cognitive capabilities of large language
models (LLMs), yet their adaptation to MLLMs is hindered by heightened risks of
hallucination in cross-modality comprehension. In this paper, we find that the
thinking while looking paradigm in current multimodal CoT approaches--where
reasoning chains are generated alongside visual input--fails to mitigate
hallucinations caused by misleading images. To address these limitations, we
propose the Visual Inference Chain (VIC) framework, a novel approach that
constructs reasoning chains using textual context alone before introducing
visual input, effectively reducing cross-modal biases and enhancing multimodal
reasoning accuracy. Comprehensive evaluations demonstrate that VIC
significantly improves zero-shot performance across various vision-related
tasks, mitigating hallucinations while refining the reasoning capabilities of
MLLMs. Our code repository can be found at
https://github.com/Terry-Xu-666/visual_inference_chain.
