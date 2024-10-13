---
layout: publication
title: 'Large Language Models Are Good Prompt Learners For Low-shot Image Classification'
authors: Zheng Zhaoheng, Wei Jingmin, Hu Xuefeng, Zhu Haidong, Nevatia Ram
conference: "Arxiv"
year: 2023
bibkey: zheng2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04076"}
  - {name: "Code", url: "https://github.com/zhaohengz/LLaMP"}
tags: ['Few Shot', 'Has Code', 'Multimodal Models', 'Prompting', 'Training Techniques']
---
Low-shot image classification, where training images are limited or
inaccessible, has benefited from recent progress on pre-trained vision-language
(VL) models with strong generalizability, e.g. CLIP. Prompt learning methods
built with VL models generate text features from the class names that only have
confined class-specific information. Large Language Models (LLMs), with their
vast encyclopedic knowledge, emerge as the complement. Thus, in this paper, we
discuss the integration of LLMs to enhance pre-trained VL models, specifically
on low-shot classification. However, the domain gap between language and vision
blocks the direct application of LLMs. Thus, we propose LLaMP, Large Language
Models as Prompt learners, that produces adaptive prompts for the CLIP text
encoder, establishing it as the connecting bridge. Experiments show that,
compared with other state-of-the-art prompt learning methods, LLaMP yields
better performance on both zero-shot generalization and few-shot image
classification, over a spectrum of 11 datasets. Code will be made available at:
https://github.com/zhaohengz/LLaMP.
