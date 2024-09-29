---
layout: publication
title: Finer Investigating And Enhancing Fine-grained Visual Concept Recognition In Large Vision Language Models
authors: Kim Jeonghwan, Ji Heng
conference: "Arxiv"
year: 2024
bibkey: kim2024investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16315"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Multimodal Models', 'RAG', 'Reinforcement Learning']
---
Recent advances in instruction-tuned Large Vision-Language Models (LVLMs) have imbued the models with the ability to generate high-level image-grounded explanations with ease. While such capability is largely attributed to the rich world knowledge contained within the Large Language Models (LLMs) our work reveals their shortcomings in fine-grained visual categorization (FGVC) across six different benchmark settings. Most recent state-of-the-art LVLMs like LLaVa-1.5 InstructBLIP and GPT-4V not only severely deteriorate in terms of classification performance e.g. average drop of 65.58 in EM for Stanford Dogs for LLaVA-1.5 but also struggle to generate an accurate explanation with detailed attributes based on the concept that appears within an input image despite their capability to generate holistic image-level descriptions. In-depth analyses show that instruction-tuned LVLMs exhibit modality gap showing discrepancy when given textual and visual inputs that correspond to the same concept preventing the image modality from leveraging the rich parametric knowledge within the LLMs. In an effort to further the communitys endeavor in this direction we propose a multiple granularity attribute-centric evaluation benchmark Finer which aims to establish a ground to evaluate LVLMs fine-grained visual comprehension ability and provide significantly improved explainability.
