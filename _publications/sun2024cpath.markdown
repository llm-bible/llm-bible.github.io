---
layout: publication
title: 'Cpath-omni: A Unified Multimodal Foundation Model For Patch And Whole Slide Image Analysis In Computational Pathology'
authors: Yuxuan Sun, Yixuan Si, Chenglu Zhu, Xuan Gong, Kai Zhang, Pingyi Chen, Ye Zhang, Zhongyi Shui, Tao Lin, Lin Yang
conference: "Arxiv"
year: 2024
bibkey: sun2024cpath
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12077"}
tags: ['Multimodal Models', 'Training Techniques', 'Few-Shot', 'Prompting', 'Applications']
---
The emergence of large multimodal models (LMMs) has brought significant
advancements to pathology. Previous research has primarily focused on
separately training patch-level and whole-slide image (WSI)-level models,
limiting the integration of learned knowledge across patches and WSIs, and
resulting in redundant models. In this work, we introduce CPath-Omni, the first
15-billion-parameter LMM designed to unify both patch and WSI level image
analysis, consolidating a variety of tasks at both levels, including
classification, visual question answering, captioning, and visual referring
prompting. Extensive experiments demonstrate that CPath-Omni achieves
state-of-the-art (SOTA) performance across seven diverse tasks on 39 out of 42
datasets, outperforming or matching task-specific models trained for individual
tasks. Additionally, we develop a specialized pathology CLIP-based visual
processor for CPath-Omni, CPath-CLIP, which, for the first time, integrates
different vision models and incorporates a large language model as a text
encoder to build a more powerful CLIP model, which achieves SOTA performance on
nine zero-shot and four few-shot datasets. Our findings highlight CPath-Omni's
ability to unify diverse pathology tasks, demonstrating its potential to
streamline and advance the field of foundation model in pathology.
