---
layout: publication
title: 'Mozart''s Touch: A Lightweight Multi-modal Music Generation Framework Based On Pre-trained Large Models'
authors: Jiajun Li, Tianze Xu, Xuesong Chen, Xinrui Yao, Shuchang Liu
conference: "Arxiv"
year: 2024
bibkey: li2024lightweight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02801"}
  - {name: "Code", url: "https://github.com/TiffanyBlews/MozartsTouch"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Tools', 'Ethics and Bias', 'Pretraining Methods', 'Interpretability', 'Fine-Tuning', 'Has Code', 'Prompting']
---
In recent years, AI-Generated Content (AIGC) has witnessed rapid
advancements, facilitating the creation of music, images, and other artistic
forms across a wide range of industries. However, current models for image- and
video-to-music synthesis struggle to capture the nuanced emotions and
atmosphere conveyed by visual content. To fill this gap, we propose Mozart's
Touch, a multi-modal music generation framework capable of generating music
aligned with cross-modal inputs such as images, videos, and text. The framework
consists of three key components: Multi-modal Captioning Module, Large Language
Model (LLM) understanding \& Bridging Module, and Music Generation Module.
Unlike traditional end-to-end methods, Mozart's Touch uses LLMs to accurately
interpret visual elements without requiring the training or fine-tuning of
music generation models, providing efficiency and transparency through clear,
interpretable prompts. We also introduce the "LLM-Bridge" method to resolve the
heterogeneous representation challenges between descriptive texts from
different modalities. Through a series of objective and subjective evaluations,
we demonstrate that Mozart's Touch outperforms current state-of-the-art models.
Our code and examples are available at
https://github.com/TiffanyBlews/MozartsTouch.
