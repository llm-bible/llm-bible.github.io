---
layout: publication
title: 'INTERS: Unlocking The Power Of Large Language Models In Search With Instruction Tuning'
authors: Yutao Zhu, Peitian Zhang, Chenghao Zhang, Yifei Chen, Binyu Xie, Zheng Liu, Ji-rong Wen, Zhicheng Dou
conference: "Arxiv"
year: 2024
bibkey: zhu2024unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06532"}
  - {name: "Code", url: "https://github.com/DaoD/INTERS"}
tags: ['Prompting', 'Has Code', 'Applications', 'Few-Shot']
---
Large language models (LLMs) have demonstrated impressive capabilities in
various natural language processing tasks. Despite this, their application to
information retrieval (IR) tasks is still challenging due to the infrequent
occurrence of many IR-specific concepts in natural language. While prompt-based
methods can provide task descriptions to LLMs, they often fall short in
facilitating a comprehensive understanding and execution of IR tasks, thereby
limiting LLMs' applicability. To address this gap, in this work, we explore the
potential of instruction tuning to enhance LLMs' proficiency in IR tasks. We
introduce a novel instruction tuning dataset, INTERS, encompassing 20 tasks
across three fundamental IR categories: query understanding, document
understanding, and query-document relationship understanding. The data are
derived from 43 distinct datasets with manually written templates. Our
empirical results reveal that INTERS significantly boosts the performance of
various publicly available LLMs, such as LLaMA, Mistral, and Phi, in IR tasks.
Furthermore, we conduct extensive experiments to analyze the effects of
instruction design, template diversity, few-shot demonstrations, and the volume
of instructions on performance. We make our dataset and the fine-tuned models
publicly accessible at https://github.com/DaoD/INTERS.
