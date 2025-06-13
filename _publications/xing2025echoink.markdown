---
layout: publication
title: 'Echoink-r1: Exploring Audio-visual Reasoning In Multimodal Llms Via Reinforcement Learning'
authors: Zhenghao Xing, Xiaowei Hu, Chi-wing Fu, Wenhai Wang, Jifeng Dai, Pheng-ann Heng
conference: "Arxiv"
year: 2025
bibkey: xing2025echoink
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.04623'}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Multimodal large language models (MLLMs) have advanced perception across
text, vision, and audio, yet they often struggle with structured cross-modal
reasoning, particularly when integrating audio and visual signals. We introduce
EchoInk-R1, a reinforcement learning framework that enhances such reasoning in
MLLMs. Built upon the Qwen2.5-Omni-7B foundation and optimized with Group
Relative Policy Optimization (GRPO), EchoInk-R1 tackles multiple-choice
question answering over synchronized audio-image pairs. To enable this, we
curate AVQA-R1-6K, a dataset pairing such audio-image inputs with
multiple-choice questions derived from OmniInstruct-v1. EchoInk-R1-7B achieves
85.77% accuracy on the validation set, outperforming the base model, which
scores 80.53%, using only 562 reinforcement learning steps. Beyond accuracy,
EchoInk-R1 demonstrates reflective reasoning by revisiting initial
interpretations and refining responses when facing ambiguous multimodal inputs.
These results suggest that lightweight reinforcement learning fine-tuning
enhances cross-modal reasoning in MLLMs. EchoInk-R1 is the first framework to
unify audio, visual, and textual modalities for general open-world reasoning
via reinforcement learning. Code and data are publicly released to facilitate
further research.
