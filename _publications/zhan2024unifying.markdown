---
layout: publication
title: Skyeyegpt Unifying Remote Sensing Vision45;language Tasks Via Instruction Tuning With Large Language Model
authors: Zhan Yang, Xiong Zhitong, Yuan Yuan
conference: "Arxiv"
year: 2024
bibkey: zhan2024unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.09712"}
  - {name: "Code", url: "https://github.com/ZhanYang&#45;nwpu/SkyEyeGPT"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Large language models (LLMs) have recently been extended to the vision45;language realm obtaining impressive general multi45;modal capabilities. However the exploration of multi45;modal large language models (MLLMs) for remote sensing (RS) data is still in its infancy and the performance is not satisfactory. In this work we introduce SkyEyeGPT a unified multi45;modal large language model specifically designed for RS vision45;language understanding. To this end we meticulously curate an RS multi45;modal instruction tuning dataset including single45;task and multi45;task conversation instructions. After manual verification we obtain a high45;quality RS instruction45;following dataset with 968k samples. Our research demonstrates that with a simple yet effective design SkyEyeGPT works surprisingly well on considerably different tasks without the need for extra encoding modules. Specifically after projecting RS visual features to the language domain via an alignment layer they are fed jointly with task45;specific instructions into an LLM45;based RS decoder to predict answers for RS open45;ended tasks. In addition we design a two45;stage tuning method to enhance instruction45;following and multi45;turn dialogue ability at different granularities. Experiments on 8 datasets for RS vision45;language tasks demonstrate SkyEyeGPTs superiority in image45;level and region45;level tasks such as captioning and visual grounding. In particular SkyEyeGPT exhibits encouraging results compared to GPT45;4V in some qualitative tests. The online demo code and dataset will be released in https://github.com/ZhanYang&#45;nwpu/SkyEyeGPT.
