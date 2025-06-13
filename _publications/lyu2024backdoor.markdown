---
layout: publication
title: 'Trojvlm: Backdoor Attack Against Vision Language Models'
authors: Weimin Lyu, Lu Pang, Tengfei Ma, Haibin Ling, Chao Chen
conference: "Arxiv"
year: 2024
bibkey: lyu2024backdoor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19232"}
tags: ['Fine-Tuning', 'Applications', 'Language Modeling', 'Security', 'Multimodal Models']
---
The emergence of Vision Language Models (VLMs) is a significant advancement
in integrating computer vision with Large Language Models (LLMs) to produce
detailed text descriptions based on visual inputs, yet it introduces new
security vulnerabilities. Unlike prior work that centered on single modalities
or classification tasks, this study introduces TrojVLM, the first exploration
of backdoor attacks aimed at VLMs engaged in complex image-to-text generation.
Specifically, TrojVLM inserts predetermined target text into output text when
encountering poisoned images. Moreover, a novel semantic preserving loss is
proposed to ensure the semantic integrity of the original image content. Our
evaluation on image captioning and visual question answering (VQA) tasks
confirms the effectiveness of TrojVLM in maintaining original semantic content
while triggering specific target text outputs. This study not only uncovers a
critical security risk in VLMs and image-to-text generation but also sets a
foundation for future research on securing multimodal models against such
sophisticated threats.
