---
layout: publication
title: 'Think Before You Segment: High-quality Reasoning Segmentation With GPT Chain Of Thoughts'
authors: Shiu-hong Kao, Yu-wing Tai, Chi-keung Tang
conference: "Arxiv"
year: 2025
bibkey: kao2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07503"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Reasoning segmentation is a challenging vision-language task that aims to
output the segmentation mask with respect to a complex, implicit, and even
non-visual query text. Previous works incorporated multimodal Large Language
Models (MLLMs) with segmentation models to approach the difficult problem.
However, their segmentation quality often falls short in complex cases,
particularly when dealing with out-of-domain objects with intricate structures,
blurry boundaries, occlusions, or high similarity with surroundings. In this
paper, we introduce ThinkFirst, a training-free reasoning segmentation
framework that leverages GPT's chain of thought to address these challenging
cases. Our approach allows GPT-4o or other powerful MLLMs to generate a
detailed, chain-of-thought description of an image. This summarized description
is then passed to a language-instructed segmentation assistant to aid the
segmentation process. Our framework allows users to easily interact with the
segmentation agent using multimodal inputs, such as easy text and image
scribbles, for successive refinement or communication. We evaluate the
performance of ThinkFirst on diverse objects. Extensive experiments show that,
this zero-shot-CoT approach significantly improves the vanilla reasoning
segmentation agent, both qualitatively and quantitatively, while being less
sensitive or critical to user-supplied prompts after Thinking First.
