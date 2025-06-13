---
layout: publication
title: 'Video-salmonn-o1: Reasoning-enhanced Audio-visual Large Language Model'
authors: Guangzhi Sun, Yudong Yang, Jimin Zhuang, Changli Tang, Yixuan Li, Wei Li, Zejun Ma, Chao Zhang
conference: "Arxiv"
year: 2025
bibkey: sun2025video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11775"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
While recent advancements in reasoning optimization have significantly
enhanced the capabilities of large language models (LLMs), existing efforts to
improve reasoning have been limited to solving mathematical problems and
focusing on visual graphical inputs, neglecting broader applications in general
video understanding.This paper proposes video-SALMONN-o1, the first open-source
reasoning-enhanced audio-visual LLM designed for general video understanding
tasks. To enhance its reasoning abilities, we develop a reasoning-intensive
dataset featuring challenging audio-visual questions with step-by-step
solutions. We also propose process direct preference optimization (pDPO), which
leverages contrastive step selection to achieve efficient step-level reward
modelling tailored for multimodal inputs. Additionally, we introduce RivaBench,
the first reasoning-intensive video understanding benchmark, featuring over
4,000 high-quality, expert-curated question-answer pairs across scenarios such
as standup comedy, academic presentations, and synthetic video detection.
video-SALMONN-o1 achieves 3-8% accuracy improvements over the LLaVA-OneVision
baseline across different video reasoning benchmarks. Besides, pDPO achieves
6-8% improvements compared to the supervised fine-tuning model on RivaBench.
Enhanced reasoning enables video-SALMONN-o1 zero-shot synthetic video detection
capabilities.
