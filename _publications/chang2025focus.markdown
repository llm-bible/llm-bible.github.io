---
layout: publication
title: 'Focus On What Matters: Enhancing Medical Vision-language Models With Automatic Attention Alignment Tuning'
authors: Aofei Chang, Le Huang, Alex James Boyd, Parminder Bhatia, Taha Kass-hout, Cao Xiao, Fenglong Ma
conference: "Arxiv"
year: 2025
bibkey: chang2025focus
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18503"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Medical Large Vision-Language Models (Med-LVLMs) often exhibit suboptimal attention distribution on visual inputs, leading to hallucinated or inaccurate outputs. Existing mitigation methods primarily rely on inference-time interventions, which are limited in attention adaptation or require additional supervision. To address this, we propose A\\(^3\\)Tune, a novel fine-tuning framework for Automatic Attention Alignment Tuning. A\\(^3\\)Tune leverages zero-shot weak labels from SAM, refines them into prompt-aware labels using BioMedCLIP, and then selectively modifies visually-critical attention heads to improve alignment while minimizing interference. Additionally, we introduce a A\\(^3\\)MoE module, enabling adaptive parameter selection for attention tuning across diverse prompts and images. Extensive experiments on medical VQA and report generation benchmarks show that A\\(^3\\)Tune outperforms state-of-the-art baselines, achieving enhanced attention distributions and performance in Med-LVLMs.
