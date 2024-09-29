---
layout: publication
title: Mm45;instruct Generated Visual Instructions For Large Multimodal Model Alignment
authors: Liu Jihao, Huang Xin, Zheng Jinliang, Liu Boxiao, Wang Jia, Yoshie Osamu, Liu Yu, Li Hongsheng
conference: "Arxiv"
year: 2024
bibkey: liu2024mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19736"}
  - {name: "Code", url: "https://github.com/jihaonew/MM&#45;Instruct"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
This paper introduces MM45;Instruct a large45;scale dataset of diverse and high45;quality visual instruction data designed to enhance the instruction45;following capabilities of large multimodal models (LMMs). While existing visual instruction datasets often focus on question45;answering they struggle to generalize to broader application scenarios such as creative writing summarization or image analysis. To address these limitations we propose a novel approach to constructing MM45;Instruct that leverages the strong instruction45;following capabilities of existing LLMs to generate novel visual instruction data from large45;scale but conventional image captioning datasets. MM45;Instruct first leverages ChatGPT to automatically generate diverse instructions from a small set of seed instructions through augmenting and summarization. It then matches these instructions with images and uses an open45;sourced large language model (LLM) to generate coherent answers to the instruction45;image pairs. The LLM is grounded by the detailed text descriptions of images in the whole answer generation process to guarantee the alignment of the instruction data. Moreover we introduce a benchmark based on the generated instruction data to evaluate the instruction45;following capabilities of existing LMMs. We demonstrate the effectiveness of MM45;Instruct by training a LLaVA45;1.5 model on the generated data denoted as LLaVA45;Instruct which exhibits significant improvements in instruction45;following capabilities compared to LLaVA45;1.5 models. The MM45;Instruct dataset benchmark and pre45;trained models are available at https://github.com/jihaonew/MM&#45;Instruct.
