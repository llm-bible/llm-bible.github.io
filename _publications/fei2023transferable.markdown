---
layout: publication
title: Transferable Decoding With Visual Entities For Zero45;shot Image Captioning
authors: Fei Junjie, Wang Teng, Zhang Jinrui, He Zhenyu, Wang Chengjie, Zheng Feng
conference: "Arxiv"
year: 2023
bibkey: fei2023transferable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.16525"}
  - {name: "Code", url: "https://github.com/FeiElysia/ViECap"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Image45;to45;text generation aims to describe images using natural language. Recently zero45;shot image captioning based on pre45;trained vision45;language models (VLMs) and large language models (LLMs) has made significant progress. However we have observed and empirically demonstrated that these methods are susceptible to modality bias induced by LLMs and tend to generate descriptions containing objects (entities) that do not actually exist in the image but frequently appear during training (i.e. object hallucination). In this paper we propose ViECap a transferable decoding model that leverages entity45;aware decoding to generate descriptions in both seen and unseen scenarios. ViECap incorporates entity45;aware hard prompts to guide LLMs attention toward the visual entities present in the image enabling coherent caption generation across diverse scenes. With entity45;aware hard prompts ViECap is capable of maintaining performance when transferring from in45;domain to out45;of45;domain scenarios. Extensive experiments demonstrate that ViECap sets a new state45;of45;the45;art cross45;domain (transferable) captioning and performs competitively in45;domain captioning compared to previous VLMs45;based zero45;shot methods. Our code is available at https://github.com/FeiElysia/ViECap
