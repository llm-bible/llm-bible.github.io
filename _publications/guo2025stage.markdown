---
layout: publication
title: 'STAR: Stage-wise Attention-guided Token Reduction For Efficient Large Vision-language Models Inference'
authors: Yichen Guo, Hanze Li, Zonghao Zhang, Jinhao You, Kai Tang, Xiande Huang
conference: "Arxiv"
year: 2025
bibkey: guo2025stage
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12359'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Pruning', 'Multimodal Models', 'Reinforcement Learning']
---
Although large vision-language models (LVLMs) leverage rich visual token representations to achieve strong performance on multimodal tasks, these tokens also introduce significant computational overhead during inference. Existing training-free token pruning methods typically adopt a single-stage strategy, focusing either on visual self-attention or visual-textual cross-attention. However, such localized perspectives often overlook the broader information flow across the model, leading to substantial performance degradation, especially under high pruning ratios. In this work, we propose STAR (Stage-wise Attention-guided token Reduction), a training-free, plug-and-play framework that approaches token pruning from a global perspective. Instead of pruning at a single point, STAR performs attention-guided reduction in two complementary stages: an early-stage pruning based on visual self-attention to remove redundant low-level features, and a later-stage pruning guided by cross-modal attention to discard task-irrelevant tokens. This holistic approach allows STAR to significantly reduce computational cost while better preserving task-critical information. Extensive experiments across multiple LVLM architectures and benchmarks show that STAR achieves strong acceleration while maintaining comparable, and in some cases even improved performance.
