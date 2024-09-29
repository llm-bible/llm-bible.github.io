---
layout: publication
title: Cross-modal Safety Alignment Is Textual Unlearning All You Need
authors: Chakraborty Trishna, Shayegani Erfan, Cai Zikui, Abu-ghazaleh Nael, Asif M. Salman, Dong Yue, Roy-chowdhury Amit K., Song Chengyu
conference: "Arxiv"
year: 2024
bibkey: chakraborty2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02575"}
tags: ['Agentic', 'Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Recent studies reveal that integrating new modalities into Large Language Models (LLMs) such as Vision-Language Models (VLMs) creates a new attack surface that bypasses existing safety training techniques like Supervised Fine-tuning (SFT) and Reinforcement Learning with Human Feedback (RLHF). While further SFT and RLHF-based safety training can be conducted in multi-modal settings collecting multi-modal training datasets poses a significant challenge. Inspired by the structural design of recent multi-modal models where regardless of the combination of input modalities all inputs are ultimately fused into the language space we aim to explore whether unlearning solely in the textual domain can be effective for cross-modality safety alignment. Our evaluation across six datasets empirically demonstrates the transferability -- textual unlearning in VLMs significantly reduces the Attack Success Rate (ASR) to less than 837; and in some cases even as low as nearly 237; for both text-based and vision-text-based attacks alongside preserving the utility. Moreover our experiments show that unlearning with a multi-modal dataset offers no potential benefits but incurs significantly increased computational demands possibly up to 6 times higher.
