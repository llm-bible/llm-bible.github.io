---
layout: publication
title: 'Frozen Large Language Models Can Perceive Paralinguistic Aspects Of Speech'
authors: Wonjune Kang, Junteng Jia, Chunyang Wu, Wei Zhou, Egor Lakomkin, Yashesh Gaur, Leda Sari, Suyoun Kim, Ke Li, Jay Mahadeokar, Ozlem Kalinli
conference: "Arxiv"
year: 2024
bibkey: kang2024frozen
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01162"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
This work studies the capabilities of a large language model (LLM) to understand paralinguistic aspects of speech without fine-tuning its weights. We utilize an end-to-end system with a speech encoder, which is trained to produce token embeddings such that the LLM's response to an expressive speech prompt is aligned with its response to a semantically matching text prompt that has also been conditioned on the user's speaking style. This framework enables the encoder to generate tokens that capture both linguistic and paralinguistic information and effectively convey them to the LLM, even when the LLM's weights remain completely frozen. To the best of our knowledge, our work is the first to explore how to induce a frozen LLM to understand more than just linguistic content from speech inputs in a general interaction setting. Experiments demonstrate that our system is able to produce higher quality and more empathetic responses to expressive speech prompts compared to several baselines.
