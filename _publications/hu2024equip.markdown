---
layout: publication
title: ELLA Equip Diffusion Models With LLM For Enhanced Semantic Alignment
authors: Hu Xiwei, Wang Rui, Fang Yixiao, Fu Bin, Cheng Pei, Yu Gang
conference: "Arxiv"
year: 2024
bibkey: hu2024equip
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.05135"}
tags: ['Merging', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Diffusion models have demonstrated remarkable performance in the domain of text45;to45;image generation. However most widely used models still employ CLIP as their text encoder which constrains their ability to comprehend dense prompts encompassing multiple objects detailed attributes complex relationships long45;text alignment etc. In this paper we introduce an Efficient Large Language Model Adapter termed ELLA which equips text45;to45;image diffusion models with powerful Large Language Models (LLM) to enhance text alignment without training of either U45;Net or LLM. To seamlessly bridge two pre45;trained models we investigate a range of semantic alignment connector designs and propose a novel module the Timestep45;Aware Semantic Connector (TSC) which dynamically extracts timestep45;dependent conditions from LLM. Our approach adapts semantic features at different stages of the denoising process assisting diffusion models in interpreting lengthy and intricate prompts over sampling timesteps. Additionally ELLA can be readily incorporated with community models and tools to improve their prompt45;following capabilities. To assess text45;to45;image models in dense prompt following we introduce Dense Prompt Graph Benchmark (DPG45;Bench) a challenging benchmark consisting of 1K dense prompts. Extensive experiments demonstrate the superiority of ELLA in dense prompt following compared to state45;of45;the45;art methods particularly in multiple object compositions involving diverse attributes and relationships.
