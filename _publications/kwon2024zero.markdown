---
layout: publication
title: Zero-shot Text-guided Infinite Image Synthesis with LLM guidance
authors: Kwon Soyeong, Lee Taegyeong, Kim Taehwan
conference: "Arxiv"
year: 2024
bibkey: kwon2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12642"}
tags: ['ARXIV', 'Applications', 'LLM', 'Merging', 'Reinforcement Learning']
---
Text-guided image editing and generation methods have diverse real-world applications. However text-guided infinite image synthesis faces several challenges. First there is a lack of text-image paired datasets with high-resolution and contextual diversity. Second expanding images based on text requires global coherence and rich local context understanding. Previous studies have mainly focused on limited categories such as natural landscapes and also required to train on high-resolution images with paired text. To address these challenges we propose a novel approach utilizing Large Language Models (LLMs) for both global coherence and local context understanding without any high-resolution text-image paired training dataset. We train the diffusion model to expand an image conditioned on global and local captions generated from the LLM and visual feature. At the inference stage given an image and a global caption we use the LLM to generate a next local caption to expand the input image. Then we expand the image using the global caption generated local caption and the visual feature to consider global consistency and spatial local context. In experiments our model outperforms the baselines both quantitatively and qualitatively. Furthermore our model demonstrates the capability of text-guided arbitrary-sized image generation in zero-shot manner with LLM guidance.
