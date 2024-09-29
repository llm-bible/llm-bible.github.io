---
layout: publication
title: Long-clip Unlocking The Long-text Capability Of CLIP
authors: Zhang Beichen, Zhang Pan, Dong Xiaoyi, Zang Yuhang, Wang Jiaqi
conference: "Arxiv"
year: 2024
bibkey: zhang2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15378"}
tags: ['Applications', 'Fine Tuning', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Contrastive Language-Image Pre-training (CLIP) has been the cornerstone for zero-shot classification text-image retrieval and text-image generation by aligning image and text modalities. Despite its widespread adoption a significant limitation of CLIP lies in the inadequate length of text input. The length of the text token is restricted to 77 and an empirical study shows the actual effective length is even less than 20. This prevents CLIP from handling detailed descriptions limiting its applications for image retrieval and text-to-image generation with extensive prerequisites. To this end we propose Long-CLIP as a plug-and-play alternative to CLIP that supports long-text input retains or even surpasses its zero-shot generalizability and aligns the CLIP latent space making it readily replace CLIP without any further adaptation in downstream frameworks. Nevertheless achieving this goal is far from straightforward as simplistic fine-tuning can result in a significant degradation of CLIPs performance. Moreover substituting the text encoder with a language model supporting longer contexts necessitates pretraining with vast amounts of data incurring significant expenses. Accordingly Long-CLIP introduces an efficient fine-tuning solution on CLIP with two novel strategies designed to maintain the original capabilities including (1) a knowledge-preserved stretching of positional embedding and (2) a primary component matching of CLIP features. With leveraging just one million extra long text-image pairs Long-CLIP has shown the superiority to CLIP for about 2037; in long caption text-image retrieval and 637; in traditional text-image retrieval tasks e.g. COCO and Flickr30k. Furthermore Long-CLIP offers enhanced capabilities for generating images from detailed text descriptions by replacing CLIP in a plug-and-play manner.
