---
layout: publication
title: 'Diffsensei: Bridging Multi-modal Llms And Diffusion Models For Customized Manga Generation'
authors: Jianzong Wu, Chao Tang, Jingbo Wang, Yanhong Zeng, Xiangtai Li, Yunhai Tong
conference: "Arxiv"
year: 2024
bibkey: wu2024bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07589'}
tags: ['Attention Mechanism', 'Model Architecture', 'Tools', 'Merging', 'Multimodal Models', 'Reinforcement Learning']
---
Story visualization, the task of creating visual narratives from textual
descriptions, has seen progress with text-to-image generation models. However,
these models often lack effective control over character appearances and
interactions, particularly in multi-character scenes. To address these
limitations, we propose a new task: \textbf\{customized manga generation\} and
introduce \textbf\{DiffSensei\}, an innovative framework specifically designed
for generating manga with dynamic multi-character control. DiffSensei
integrates a diffusion-based image generator with a multimodal large language
model (MLLM) that acts as a text-compatible identity adapter. Our approach
employs masked cross-attention to seamlessly incorporate character features,
enabling precise layout control without direct pixel transfer. Additionally,
the MLLM-based adapter adjusts character features to align with panel-specific
text cues, allowing flexible adjustments in character expressions, poses, and
actions. We also introduce \textbf\{MangaZero\}, a large-scale dataset tailored
to this task, containing 43,264 manga pages and 427,147 annotated panels,
supporting the visualization of varied character interactions and movements
across sequential frames. Extensive experiments demonstrate that DiffSensei
outperforms existing models, marking a significant advancement in manga
generation by enabling text-adaptable character customization. The project page
is https://jianzongwu.github.io/projects/diffsensei/.
