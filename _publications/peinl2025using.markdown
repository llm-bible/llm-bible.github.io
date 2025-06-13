---
layout: publication
title: 'Using Llms As Prompt Modifier To Avoid Biases In AI Image Generators'
authors: René Peinl
conference: "Arxiv"
year: 2025
bibkey: peinl2025using
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11104"}
tags: ['Merging', 'Prompting', 'Ethics and Bias', 'Reinforcement Learning']
---
This study examines how Large Language Models (LLMs) can reduce biases in
text-to-image generation systems by modifying user prompts. We define bias as a
model's unfair deviation from population statistics given neutral prompts. Our
experiments with Stable Diffusion XL, 3.5 and Flux demonstrate that
LLM-modified prompts significantly increase image diversity and reduce bias
without the need to change the image generators themselves. While occasionally
producing results that diverge from original user intent for elaborate prompts,
this approach generally provides more varied interpretations of underspecified
requests rather than superficial variations. The method works particularly well
for less advanced image generators, though limitations persist for certain
contexts like disability representation. All prompts and generated images are
available at https://iisys-hof.github.io/llm-prompt-img-gen/
