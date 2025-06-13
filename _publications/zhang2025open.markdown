---
layout: publication
title: 'Open Eyes, Then Reason: Fine-grained Visual Mathematical Understanding In Mllms'
authors: Shan Zhang, Aotian Chen, Yanpeng Sun, Jindong Gu, Yi-yu Zheng, Piotr Koniusz, Kai Zou, Anton Van Den Hengel, Yuan Xue
conference: "Arxiv"
year: 2025
bibkey: zhang2025open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06430"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Prompting', 'Pre-Training']
---
Current multimodal large language models (MLLMs) often underperform on
mathematical problem-solving tasks that require fine-grained visual
understanding. The limitation is largely attributable to inadequate perception
of geometric primitives during image-level contrastive pre-training (e.g.,
CLIP). While recent efforts to improve math MLLMs have focused on scaling up
mathematical visual instruction datasets and employing stronger LLM backbones,
they often overlook persistent errors in visual recognition. In this paper, we
systematically evaluate the visual grounding capabilities of state-of-the-art
MLLMs and reveal a significant negative correlation between visual grounding
accuracy and problem-solving performance, underscoring the critical role of
fine-grained visual understanding. Notably, advanced models like GPT-4o exhibit
a 70% error rate when identifying geometric entities, highlighting that this
remains a key bottleneck in visual mathematical reasoning. To address this, we
propose a novel approach, SVE-Math (Selective Vision-Enhanced Mathematical
MLLM), featuring a geometric-grounded vision encoder and a feature router that
dynamically adjusts the contribution of hierarchical visual feature maps. Our
model recognizes accurate visual primitives and generates precise visual
prompts tailored to the language model's reasoning needs. In experiments,
SVE-Math-Qwen2.5-7B outperforms other 7B models by 15% on MathVerse and is
compatible with GPT-4V on MathVista. Despite being trained on smaller datasets,
SVE-Math-7B achieves competitive performance on GeoQA, rivaling models trained
on significantly larger datasets. Our findings emphasize the importance of
incorporating fine-grained visual understanding into MLLMs and provide a
promising direction for future research.
