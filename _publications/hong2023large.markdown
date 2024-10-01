---
layout: publication
title: 'Direct2v: Large Language Models Are Frame-level Directors For Zero-shot Text-to-video Generation'
authors: Hong Susung, Seo Junyoung, Shin Heeseong, Hong Sunghwan, Kim Seungryong
conference: "Arxiv"
year: 2023
bibkey: hong2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14330"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
In the paradigm of AI-generated content (AIGC), there has been increasing attention to transferring knowledge from pre-trained text-to-image (T2I) models to text-to-video (T2V) generation. Despite their effectiveness, these frameworks face challenges in maintaining consistent narratives and handling shifts in scene composition or object placement from a single abstract user prompt. Exploring the ability of large language models (LLMs) to generate time-dependent, frame-by-frame prompts, this paper introduces a new framework, dubbed DirecT2V. DirecT2V leverages instruction-tuned LLMs as directors, enabling the inclusion of time-varying content and facilitating consistent video generation. To maintain temporal consistency and prevent mapping the value to a different object, we equip a diffusion model with a novel value mapping method and dual-softmax filtering, which do not require any additional training. The experimental results validate the effectiveness of our framework in producing visually coherent and storyful videos from abstract user prompts, successfully addressing the challenges of zero-shot video generation.
