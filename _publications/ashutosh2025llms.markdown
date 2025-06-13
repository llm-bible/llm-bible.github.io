---
layout: publication
title: 'Llms Can See And Hear Without Any Training'
authors: Kumar Ashutosh, Yossi Gandelsman, Xinlei Chen, Ishan Misra, Rohit Girdhar
conference: "Arxiv"
year: 2025
bibkey: ashutosh2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18096"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'RAG', 'Prompting', 'Applications']
---
We present MILS: Multimodal Iterative LLM Solver, a surprisingly simple,
training-free approach, to imbue multimodal capabilities into your favorite
LLM. Leveraging their innate ability to perform multi-step reasoning, MILS
prompts the LLM to generate candidate outputs, each of which are scored and fed
back iteratively, eventually generating a solution to the task. This enables
various applications that typically require training specialized models on
task-specific data. In particular, we establish a new state-of-the-art on
emergent zero-shot image, video and audio captioning. MILS seamlessly applies
to media generation as well, discovering prompt rewrites to improve
text-to-image generation, and even edit prompts for style transfer! Finally,
being a gradient-free optimization approach, MILS can invert multimodal
embeddings into text, enabling applications like cross-modal arithmetic.
