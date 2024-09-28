---
layout: publication
title: Mastering Text-to-Image Diffusion Recaptioning Planning and Generating with Multimodal LLMs
authors: Yang Ling, Yu Zhaochen, Meng Chenlin, Xu Minkai, Ermon Stefano, Cui Bin
conference: "Arxiv"
year: 2024
bibkey: yang2024mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11708"}
  - {name: "Code", url: "https://github.com/YangLing0818/RPG-DiffusionMaster"}
tags: ['ARXIV', 'GPT', 'Has Code', 'LLM', 'Merging', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Diffusion models have exhibit exceptional performance in text-to-image generation and editing. However existing methods often face challenges when handling complex text prompts that involve multiple objects with multiple attributes and relationships. In this paper we propose a brand new training-free text-to-image generation/editing framework namely Recaption Plan and Generate (RPG) harnessing the powerful chain-of-thought reasoning ability of multimodal LLMs to enhance the compositionality of text-to-image diffusion models. Our approach employs the MLLM as a global planner to decompose the process of generating complex images into multiple simpler generation tasks within subregions. We propose complementary regional diffusion to enable region-wise compositional generation. Furthermore we integrate text-guided image generation and editing within the proposed RPG in a closed-loop fashion thereby enhancing generalization ability. Extensive experiments demonstrate our RPG outperforms state-of-the-art text-to-image diffusion models including DALL-E 3 and SDXL particularly in multi-category object composition and text-image semantic alignment. Notably our RPG framework exhibits wide compatibility with various MLLM architectures (e.g. MiniGPT-4) and diffusion backbones (e.g. ControlNet). Our code is available at https://github.com/YangLing0818/RPG-DiffusionMaster
