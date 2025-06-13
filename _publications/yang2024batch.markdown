---
layout: publication
title: 'Batch-instructed Gradient For Prompt Evolution:systematic Prompt Optimization For Enhanced Text-to-image Synthesis'
authors: Xinrui Yang, Zhuohan Wang, Anthony Hu
conference: "Arxiv"
year: 2024
bibkey: yang2024batch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.08713"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'Prompting', 'Attention Mechanism']
---
Text-to-image models have shown remarkable progress in generating
high-quality images from user-provided prompts. Despite this, the quality of
these images varies due to the models' sensitivity to human language nuances.
With advancements in large language models, there are new opportunities to
enhance prompt design for image generation tasks. Existing research primarily
focuses on optimizing prompts for direct interaction, while less attention is
given to scenarios involving intermediary agents, like the Stable Diffusion
model. This study proposes a Multi-Agent framework to optimize input prompts
for text-to-image generation models. Central to this framework is a prompt
generation mechanism that refines initial queries using dynamic instructions,
which evolve through iterative performance feedback. High-quality prompts are
then fed into a state-of-the-art text-to-image model. A professional prompts
database serves as a benchmark to guide the instruction modifier towards
generating high-caliber prompts. A scoring system evaluates the generated
images, and an LLM generates new instructions based on calculated gradients.
This iterative process is managed by the Upper Confidence Bound (UCB) algorithm
and assessed using the Human Preference Score version 2 (HPS v2). Preliminary
ablation studies highlight the effectiveness of various system components and
suggest areas for future improvements.
