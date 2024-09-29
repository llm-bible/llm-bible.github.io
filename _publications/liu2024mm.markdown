---
layout: publication
title: MM-Instruct Generated Visual Instructions for Large Multimodal Model Alignment
authors: Liu Jihao, Huang Xin, Zheng Jinliang, Liu Boxiao, Wang Jia, Yoshie Osamu, Liu Yu, Li Hongsheng
conference: "Arxiv"
year: 2024
bibkey: liu2024mm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19736"}
  - {name: "Code", url: "https://github.com/jihaonew/MM-Instruct"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
This paper introduces MM-Instruct a large-scale dataset of diverse and high-quality visual instruction data designed to enhance the instruction-following capabilities of large multimodal models (LMMs). While existing visual instruction datasets often focus on question-answering they struggle to generalize to broader application scenarios such as creative writing summarization or image analysis. To address these limitations we propose a novel approach to constructing MM-Instruct that leverages the strong instruction-following capabilities of existing LLMs to generate novel visual instruction data from large-scale but conventional image captioning datasets. MM-Instruct first leverages ChatGPT to automatically generate diverse instructions from a small set of seed instructions through augmenting and summarization. It then matches these instructions with images and uses an open-sourced large language model (LLM) to generate coherent answers to the instruction-image pairs. The LLM is grounded by the detailed text descriptions of images in the whole answer generation process to guarantee the alignment of the instruction data. Moreover we introduce a benchmark based on the generated instruction data to evaluate the instruction-following capabilities of existing LMMs. We demonstrate the effectiveness of MM-Instruct by training a LLaVA-1.5 model on the generated data denoted as LLaVA-Instruct which exhibits significant improvements in instruction-following capabilities compared to LLaVA-1.5 models. The MM-Instruct dataset benchmark and pre-trained models are available at https://github.com/jihaonew/MM-Instruct.
