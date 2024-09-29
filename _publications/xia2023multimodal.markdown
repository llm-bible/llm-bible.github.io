---
layout: publication
title: "LLMGA: Multimodal Large Language Model Based Generation Assistant"
authors: Xia Bin, Wang Shiyin, Tao Yingfan, Wang Yitong, Jia Jiaya
conference: "Arxiv"
year: 2023
bibkey: xia2023multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16500"}
tags: ['Applications', 'Interpretability And Explainability', 'Merging', 'Multimodal Models', 'Prompting', 'RAG', 'Training Techniques']
---
In this paper we introduce a Multimodal Large Language Model-based Generation Assistant (LLMGA) leveraging the vast reservoir of knowledge and proficiency in reasoning comprehension and response inherent in Large Language Models (LLMs) to assist users in image generation and editing. Diverging from existing approaches where Multimodal Large Language Models (MLLMs) generate fixed-size embeddings to control Stable Diffusion (SD) our LLMGA provides a detailed language generation prompt for precise control over SD. This not only augments LLM context understanding but also reduces noise in generation prompts yields images with more intricate and precise content and elevates the interpretability of the network. To this end we curate a comprehensive dataset comprising prompt refinement similar image generation inpainting amp; outpainting and instruction-based editing. Moreover we propose a two-stage training scheme. In the first stage we train the MLLM to grasp the properties of image generation and editing enabling it to generate detailed prompts. In the second stage we optimize SD to align with the MLLMs generation prompts. Additionally we propose a reference-based restoration network to alleviate texture brightness and contrast disparities between generated and preserved regions during inpainting and outpainting. Extensive results show that LLMGA has promising generation and editing capabilities and can enable more flexible and expansive applications in an interactive manner.
