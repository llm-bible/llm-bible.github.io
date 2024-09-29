---
layout: publication
title: VP-LLM Text-driven 3D Volume Completion With Large Language Models Through Patchification
authors: Liu Jianmeng, Liu Yichen, Zhang Yuyao, Meng Zeyuan, Tai Yu-wing, Tang Chi-keung
conference: "Arxiv"
year: 2024
bibkey: liu2024vp
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05543"}
tags: ['BERT', 'Merging', 'Model Architecture', 'Multimodal Models', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tokenization']
---
Recent conditional 3D completion works have mainly relied on CLIP or BERT to encode textual information which cannot support complex instruction. Meanwhile large language models (LLMs) have shown great potential in multi-modal understanding and generation tasks. Inspired by the recent advancements of LLM we present Volume Patch LLM (VP-LLM) which leverages LLMs to perform conditional 3D completion in a single-forward pass. To integrate a 3D model into the LLM tokenization configuration the incomplete 3D object is first divided into small patches that can be encoded independently. These encoded patches are then fed into an LLM along with the text prompt instructing the LLM to capture the relations between these patches as well as injecting semantic meanings into the 3D object. Our results demonstrate a strong ability of LLMs to interpret complex text instructions and understand 3D objects surpassing state-of-the-art diffusion-based 3D completion models in generation quality.
