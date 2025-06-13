---
layout: publication
title: 'Mosaic-it: Cost-free Compositional Data Synthesis For Instruction Tuning'
authors: Ming Li, Pei Chen, Chenguang Wang, Hongyu Zhao, Yijun Liang, Yupeng Hou, Fuxiao Liu, Tianyi Zhou
conference: "Arxiv"
year: 2024
bibkey: li2024mosaic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.13326'}
  - {name: "Code", url: 'https://github.com/tianyi-lab/Mosaic-IT'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques']
---
Finetuning large language models with a variety of instruction-response pairs has enhanced their capability to understand and follow instructions. Current instruction tuning primarily relies on teacher models or human intervention to generate and refine the instructions and responses for training, which are costly, non-sustainable, and may lack diversity. In this paper, we introduce Mosaic Instruction Tuning (Mosaic-IT), a human/model-free compositional data synthesis method that can efficiently create rich and diverse augmentations from existing instruction tuning data to enhance the LLMs. Mosaic-IT randomly concatenates multiple instruction data into one and trains the model to produce the corresponding responses with predefined higher-level meta-instructions to strengthen its multi-step instruction-following and format-following skills. Our extensive evaluations demonstrate a superior performance and training efficiency of Mosaic-IT, which achieves consistent performance improvements over various benchmarks and an 80% reduction in training costs compared with original instruction tuning. Our codes and data are available at https://github.com/tianyi-lab/Mosaic-IT.
