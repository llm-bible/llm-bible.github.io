---
layout: publication
title: 'Parameter Efficient Reinforcement Learning From Human Feedback'
authors: Hakim Sidahmed, Samrat Phatale, Alex Hutcheson, Zhuonan Lin, Zhang Chen, Zac Yu, Jarvis Jin, Simral Chaudhary, Roman Komarytsia, Christiane Ahlheim, Yonghao Zhu, Bowen Li, Saravanan Ganesh, Bill Byrne, Jessica Hoffmann, Hassan Mansoor, Wei Li, Abhinav Rastogi, Lucas Dixon
conference: "Arxiv"
year: 2024
bibkey: sidahmed2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10704"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
While Reinforcement Learning from Human Feedback (RLHF) effectively aligns
pretrained Large Language and Vision-Language Models (LLMs, and VLMs) with
human preferences, its computational cost and complexity hamper its wider
adoption. To alleviate some of the computational burden of fine-tuning,
parameter efficient methods, like LoRA were introduced. In this work, we
empirically evaluate the setup of Parameter Efficient Reinforcement Learning
from Human Feedback (PE-RLHF) that leverages LoRA fine-tuning for Reward
Modeling, and Reinforcement Learning. We benchmark the PE-RLHF setup on six
diverse datasets spanning summarization, harmless/helpful response generation,
UI automation, and visual question answering in terms of effectiveness of the
trained models, and the training resources required. Our findings show, for the
first time, that PE-RLHF achieves comparable performance to RLHF, while
significantly reducing training time (up to 90% faster for reward models, and
30% faster for RL), and memory footprint (up to 50% reduction for reward
models, and 27% for RL). We provide comprehensive ablations across LoRA ranks,
and model sizes for both reward modeling and reinforcement learning. By
mitigating the computational burden associated with RLHF, we push for a broader
adoption of PE-RLHF as an alignment technique for LLMs and VLMs.
