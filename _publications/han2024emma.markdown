---
layout: publication
title: EMMA Your Text-to-image Diffusion Model Can Secretly Accept Multi-modal Prompts
authors: Han Yucheng, Wang Rui, Zhang Chi, Hu Juntao, Cheng Pei, Fu Bin, Zhang Hanwang
conference: "Arxiv"
year: 2024
bibkey: han2024emma
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.09162"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques', 'Transformer']
---
Recent advancements in image generation have enabled the creation of high-quality images from text conditions. However when facing multi-modal conditions such as text combined with reference appearances existing methods struggle to balance multiple conditions effectively typically showing a preference for one modality over others. To address this challenge we introduce EMMA a novel image generation model accepting multi-modal prompts built upon the state-of-the-art text-to-image (T2I) diffusion model ELLA. EMMA seamlessly incorporates additional modalities alongside text to guide image generation through an innovative Multi-modal Feature Connector design which effectively integrates textual and supplementary modal information using a special attention mechanism. By freezing all parameters in the original T2I diffusion model and only adjusting some additional layers we reveal an interesting finding that the pre-trained T2I diffusion model can secretly accept multi-modal prompts. This interesting property facilitates easy adaptation to different existing frameworks making EMMA a flexible and effective tool for producing personalized and context-aware images and even videos. Additionally we introduce a strategy to assemble learned EMMA modules to produce images conditioned on multiple modalities simultaneously eliminating the need for additional training with mixed multi-modal prompts. Extensive experiments demonstrate the effectiveness of EMMA in maintaining high fidelity and detail in generated images showcasing its potential as a robust solution for advanced multi-modal conditional image generation tasks.
