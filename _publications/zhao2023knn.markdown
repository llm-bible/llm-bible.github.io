---
layout: publication
title: Knn-icl&#58; Compositional Task-oriented Parsing Generalization With Nearest Neighbor In-context Learning
authors: Zhao Wenting, Liu Ye, Wan Yao, Wang Yibo, Wu Qingyang, Deng Zhongfen, Du Jiangshu, Liu Shuaiqi, Xu Yunlong, Yu Philip S.
conference: "Arxiv"
year: 2023
bibkey: zhao2023knn
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10771"}
tags: ['In Context Learning', 'Prompting']
---
Task-Oriented Parsing (TOP) enables conversational assistants to interpret user commands expressed in natural language transforming them into structured outputs that combine elements of both natural language and intent/slot tags. Recently Large Language Models (LLMs) have achieved impressive performance in synthesizing computer programs based on a natural language prompt mitigating the gap between natural language and structured programs. Our paper focuses on harnessing the capabilities of LLMs for semantic parsing tasks addressing the following three key research questions 1) How can LLMs be effectively utilized for semantic parsing tasks 2) What defines an effective prompt and 3) How can LLM overcome the length constraint and streamline prompt design by including all examples as prompts We introduce k Nearest Neighbor In-Context Learning(kNN-ICL) which simplifies prompt engineering by allowing it to be built on top of any design strategy while providing access to all demo examples. Extensive experiments show that 1)Simple ICL without kNN search can achieve a comparable performance with strong supervised models on the TOP tasks and 2) kNN-ICL significantly improves the comprehension of complex requests by seamlessly integrating ICL with a nearest-neighbor approach. Notably this enhancement is achieved without the need for additional data or specialized prompts.
