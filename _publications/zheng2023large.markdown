---
layout: publication
title: Large Language Models Are Good Prompt Learners For Low45;shot Image Classification
authors: Zheng Zhaoheng, Wei Jingmin, Hu Xuefeng, Zhu Haidong, Nevatia Ram
conference: "Arxiv"
year: 2023
bibkey: zheng2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04076"}
  - {name: "Code", url: "https://github.com/zhaohengz/LLaMP"}
tags: ['Has Code', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Low45;shot image classification where training images are limited or inaccessible has benefited from recent progress on pre45;trained vision45;language (VL) models with strong generalizability e.g. CLIP. Prompt learning methods built with VL models generate text features from the class names that only have confined class45;specific information. Large Language Models (LLMs) with their vast encyclopedic knowledge emerge as the complement. Thus in this paper we discuss the integration of LLMs to enhance pre45;trained VL models specifically on low45;shot classification. However the domain gap between language and vision blocks the direct application of LLMs. Thus we propose LLaMP Large Language Models as Prompt learners that produces adaptive prompts for the CLIP text encoder establishing it as the connecting bridge. Experiments show that compared with other state45;of45;the45;art prompt learning methods LLaMP yields better performance on both zero45;shot generalization and few45;shot image classification over a spectrum of 11 datasets. Code will be made available at https://github.com/zhaohengz/LLaMP.
