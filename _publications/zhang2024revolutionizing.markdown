---
layout: publication
title: 'TIE: Revolutionizing Text-based Image Editing For Complex-prompt Following And High-fidelity Editing'
authors: Xinyu Zhang, Mengxue Kang, Fei Wei, Shuang Xu, Yuhe Liu, Lin Ma
conference: "Arxiv"
year: 2024
bibkey: zhang2024revolutionizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.16803'}
tags: ['Prompting', 'Multimodal Models', 'Tools', 'Merging']
---
As the field of image generation rapidly advances, traditional diffusion
models and those integrated with multimodal large language models (LLMs) still
encounter limitations in interpreting complex prompts and preserving image
consistency pre and post-editing. To tackle these challenges, we present an
innovative image editing framework that employs the robust Chain-of-Thought
(CoT) reasoning and localizing capabilities of multimodal LLMs to aid diffusion
models in generating more refined images. We first meticulously design a CoT
process comprising instruction decomposition, region localization, and detailed
description. Subsequently, we fine-tune the LISA model, a lightweight
multimodal LLM, using the CoT process of Multimodal LLMs and the mask of the
edited image. By providing the diffusion models with knowledge of the generated
prompt and image mask, our models generate images with a superior understanding
of instructions. Through extensive experiments, our model has demonstrated
superior performance in image generation, surpassing existing state-of-the-art
models. Notably, our model exhibits an enhanced ability to understand complex
prompts and generate corresponding images, while maintaining high fidelity and
consistency in images before and after generation.
