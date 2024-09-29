---
layout: publication
title: 'Jailbreak In Pieces: Compositional Adversarial Attacks On Multi-modal Language Models'
authors: Shayegani Erfan, Dong Yue, Abu-ghazaleh Nael
conference: "Arxiv"
year: 2023
bibkey: shayegani2023jailbreak
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.14539"}
tags: ['Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security']
---
We introduce new jailbreak attacks on vision language models (VLMs) which use aligned LLMs and are resilient to text-only jailbreak attacks. Specifically we develop cross-modality attacks on alignment where we pair adversarial images going through the vision encoder with textual prompts to break the alignment of the language model. Our attacks employ a novel compositional strategy that combines an image adversarially targeted towards toxic embeddings with generic prompts to accomplish the jailbreak. Thus the LLM draws the context to answer the generic prompt from the adversarial image. The generation of benign-appearing adversarial images leverages a novel embedding-space-based methodology operating with no access to the LLM model. Instead the attacks require access only to the vision encoder and utilize one of our four embedding space targeting strategies. By not requiring access to the LLM the attacks lower the entry barrier for attackers particularly when vision encoders such as CLIP are embedded in closed-source LLMs. The attacks achieve a high success rate across different VLMs highlighting the risk of cross-modality alignment vulnerabilities and the need for new alignment approaches for multi-modal models.
