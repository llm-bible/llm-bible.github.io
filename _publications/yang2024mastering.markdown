---
layout: publication
title: Mastering Text45;to45;image Diffusion Recaptioning Planning And Generating With Multimodal Llms
authors: Yang Ling, Yu Zhaochen, Meng Chenlin, Xu Minkai, Ermon Stefano, Cui Bin
conference: "Arxiv"
year: 2024
bibkey: yang2024mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11708"}
  - {name: "Code", url: "https://github.com/YangLing0818/RPG&#45;DiffusionMaster"}
tags: ['GPT', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Diffusion models have exhibit exceptional performance in text45;to45;image generation and editing. However existing methods often face challenges when handling complex text prompts that involve multiple objects with multiple attributes and relationships. In this paper we propose a brand new training45;free text45;to45;image generation/editing framework namely Recaption Plan and Generate (RPG) harnessing the powerful chain45;of45;thought reasoning ability of multimodal LLMs to enhance the compositionality of text45;to45;image diffusion models. Our approach employs the MLLM as a global planner to decompose the process of generating complex images into multiple simpler generation tasks within subregions. We propose complementary regional diffusion to enable region45;wise compositional generation. Furthermore we integrate text45;guided image generation and editing within the proposed RPG in a closed45;loop fashion thereby enhancing generalization ability. Extensive experiments demonstrate our RPG outperforms state45;of45;the45;art text45;to45;image diffusion models including DALL45;E 3 and SDXL particularly in multi45;category object composition and text45;image semantic alignment. Notably our RPG framework exhibits wide compatibility with various MLLM architectures (e.g. MiniGPT45;4) and diffusion backbones (e.g. ControlNet). Our code is available at https://github.com/YangLing0818/RPG&#45;DiffusionMaster
