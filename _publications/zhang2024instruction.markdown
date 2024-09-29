---
layout: publication
title: Instructedit Instruction45;based Knowledge Editing For Large Language Models
authors: Zhang Ningyu, Tian Bozhong, Cheng Siyuan, Liang Xiaozhuan, Hu Yi, Xue Kouying, Gou Yanjie, Chen Xi, Chen Huajun
conference: "Arxiv"
year: 2024
bibkey: zhang2024instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.16123"}
  - {name: "Code", url: "https://github.com/zjunlp/EasyEdit"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Knowledge editing for large language models can offer an efficient solution to alter a models behavior without negatively impacting the overall performance. However the current approaches encounter issues with limited generalizability across tasks necessitating one distinct editor for each task significantly hindering the broader applications. To address this we take the first step to analyze the multi45;task generalization issue in knowledge editing. Specifically we develop an instruction45;based editing technique termed InstructEdit which facilitates the editors adaptation to various task performances simultaneously using simple instructions. With only one unified editor for each LLM we empirically demonstrate that InstructEdit can improve the editors control leading to an average 14.8637; increase in Reliability in multi45;task editing setting. Furthermore experiments involving holdout unseen task illustrate that InstructEdit consistently surpass previous strong baselines. To further investigate the underlying mechanisms of instruction45;based knowledge editing we analyze the principal components of the editing gradient directions which unveils that instructions can help control optimization direction with stronger OOD generalization. Code and datasets are available in https://github.com/zjunlp/EasyEdit.
