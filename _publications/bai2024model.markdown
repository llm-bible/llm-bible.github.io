---
layout: publication
title: Souplm Model Integration In Large Language And Multi45;modal Models
authors: Bai Yue, Zhang Zichen, Lu Jiasen, Fu Yun
conference: "Arxiv"
year: 2024
bibkey: bai2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08196"}
tags: ['Multimodal Models', 'Tools', 'Training Techniques']
---
Training large language models (LLMs) and multimodal LLMs necessitates significant computing resources and existing publicly available LLMs are typically pre45;trained on diverse privately curated datasets spanning various tasks. For instance LLaMA Vicuna and LLaVA are three LLM variants trained with LLaMA base models using very different training recipes tasks and data modalities. The training cost and complexity for such LLM variants grow rapidly. In this study we propose to use a soup strategy to assemble these LLM variants into a single well45;generalized multimodal LLM (SoupLM) in a cost45;efficient manner. Assembling these LLM variants efficiently brings knowledge and specialities trained from different domains and data modalities into an integrated one (e.g. chatbot speciality from user45;shared conversations for Vicuna and visual capacity from vision45;language data for LLaVA) therefore to avoid computing costs of repetitive training on several different domains. We propose series of soup strategies to systematically benchmark performance gains across various configurations and probe the soup behavior across base models in the interpolation space.
