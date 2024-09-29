---
layout: publication
title: LLM4GEN Leveraging Semantic Representation Of Llms For Text-to-image Generation
authors: Liu Mushui, Ma Yuhang, Zhen Yang, Dan Jun, Yu Yunlong, Zhao Zeng, Hu Zhipeng, Liu Bai, Fan Changjie
conference: "Arxiv"
year: 2024
bibkey: liu2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00737"}
tags: ['Merging', 'Multimodal Models', 'Prompting', 'RAG', 'Tools']
---
Diffusion models have exhibited substantial success in text-to-image generation. However they often encounter challenges when dealing with complex and dense prompts involving multiple objects attribute binding and long descriptions. In this paper we propose a novel framework called (textbfLLM4GEN) which enhances the semantic understanding of text-to-image diffusion models by leveraging the representation of Large Language Models (LLMs). It can be seamlessly incorporated into various diffusion models as a plug-and-play component. A specially designed Cross-Adapter Module (CAM) integrates the original text features of text-to-image models with LLM features thereby enhancing text-to-image generation. Additionally to facilitate and correct entity-attribute relationships in text prompts we develop an entity-guided regularization loss to further improve generation performance. We also introduce DensePrompts which contains 7000 dense prompts to provide a comprehensive evaluation for the text-to-image generation task. Experiments indicate that LLM4GEN significantly improves the semantic alignment of SD1.5 and SDXL demonstrating increases of 9.6937; and 12.9037; in color on T2I-CompBench respectively. Moreover it surpasses existing models in terms of sample quality image-text alignment and human evaluation.
