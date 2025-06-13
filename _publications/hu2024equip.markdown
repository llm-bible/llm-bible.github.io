---
layout: publication
title: 'ELLA: Equip Diffusion Models With LLM For Enhanced Semantic Alignment'
authors: Xiwei Hu, Rui Wang, Yixiao Fang, Bin Fu, Pei Cheng, Gang Yu
conference: "Arxiv"
year: 2024
bibkey: hu2024equip
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.05135'}
tags: ['Training Techniques', 'Tools', 'Merging', 'Prompting', 'Reinforcement Learning']
---
Diffusion models have demonstrated remarkable performance in the domain of
text-to-image generation. However, most widely used models still employ CLIP as
their text encoder, which constrains their ability to comprehend dense prompts,
encompassing multiple objects, detailed attributes, complex relationships,
long-text alignment, etc. In this paper, we introduce an Efficient Large
Language Model Adapter, termed ELLA, which equips text-to-image diffusion
models with powerful Large Language Models (LLM) to enhance text alignment
without training of either U-Net or LLM. To seamlessly bridge two pre-trained
models, we investigate a range of semantic alignment connector designs and
propose a novel module, the Timestep-Aware Semantic Connector (TSC), which
dynamically extracts timestep-dependent conditions from LLM. Our approach
adapts semantic features at different stages of the denoising process,
assisting diffusion models in interpreting lengthy and intricate prompts over
sampling timesteps. Additionally, ELLA can be readily incorporated with
community models and tools to improve their prompt-following capabilities. To
assess text-to-image models in dense prompt following, we introduce Dense
Prompt Graph Benchmark (DPG-Bench), a challenging benchmark consisting of 1K
dense prompts. Extensive experiments demonstrate the superiority of ELLA in
dense prompt following compared to state-of-the-art methods, particularly in
multiple object compositions involving diverse attributes and relationships.
