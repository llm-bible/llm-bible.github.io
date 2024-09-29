---
layout: publication
title: TroVE Inducing Verifiable and Efficient Toolboxes for Solving Programmatic Tasks
authors: Wang Zhiruo, Fried Daniel, Neubig Graham
conference: "Arxiv"
year: 2024
bibkey: wang2024trove
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12869"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Training Techniques']
---
Language models (LMs) can solve tasks such as answering questions about tables or images by writing programs. However using primitive functions often leads to verbose and error-prone programs and higher-level functions require expert design. To enable better solutions without human labor we ask code LMs to curate reusable high-level functions and use them to write solutions. We present TROVE a training-free method of inducing a verifiable and efficient toolbox of functions by generating via using growing and periodically trimming the toolbox. On 11 datasets from math table question answering and image reasoning tasks TROVE consistently yields simpler solutions with higher accuracy than baselines using CODELLAMA and previous methods using GPT while using 79-98 smaller toolboxes. TROVE further enables 31 faster and 13 more accurate human verification than baselines. With the same pipeline it creates diverse functions for varied tasks and datasets providing insights into their individual characteristics.
