---
layout: publication
title: "Video-llava: Learning United Visual Representation By Alignment Before Projection"
authors: Lin Bin, Ye Yang, Zhu Bin, Cui Jiaxi, Ning Munan, Jin Peng, Yuan Li
conference: "Arxiv"
year: 2023
bibkey: lin2023video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.10122"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Tokenization']
---
The Large Vision-Language Model (LVLM) has enhanced the performance of various downstream tasks in visual-language understanding. Most existing approaches encode images and videos into separate feature spaces which are then fed as inputs to large language models. However due to the lack of unified tokenization for images and videos namely misalignment before projection it becomes challenging for a Large Language Model (LLM) to learn multi-modal interactions from several poor projection layers. In this work we unify visual representation into the language feature space to advance the foundational LLM towards a unified LVLM. As a result we establish a simple but robust LVLM baseline Video-LLaVA which learns from a mixed dataset of images and videos mutually enhancing each other. Video-LLaVA achieves superior performances on a broad range of 9 image benchmarks across 5 image question-answering datasets and 4 image benchmark toolkits. Additionally our Video-LLaVA also outperforms Video-ChatGPT by 5.837; 9.937; 18.637; and 10.137; on MSRVTT MSVD TGIF and ActivityNet respectively. Notably extensive experiments demonstrate that Video-LLaVA mutually benefits images and videos within a unified visual representation outperforming models designed specifically for images or videos. We aim for this work to provide modest insights into the multi-modal inputs for the LLM.
