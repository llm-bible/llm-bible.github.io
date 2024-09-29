---
layout: publication
title: Revisiting Demonstration Selection Strategies In In-context Learning
authors: Peng Keqin, Ding Liang, Yuan Yancheng, Liu Xuebo, Zhang Min, Ouyang Yuanxin, Tao Dacheng
conference: "Arxiv"
year: 2024
bibkey: peng2024revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12087"}
tags: ['In Context Learning', 'Interpretability And Explainability', 'Prompting']
---
Large language models (LLMs) have shown an impressive ability to perform a wide range of tasks using in-context learning (ICL) where a few examples are used to describe a task to the model. However the performance of ICL varies significantly with the choice of demonstrations and it is still unclear why this happens or what factors will influence its choice. In this work we first revisit the factors contributing to this variance from both data and model aspects and find that the choice of demonstration is both data- and model-dependent. We further proposed a data- and model-dependent demonstration selection method (textbf)TopK + ConE based on the assumption that (textit)the performance of a demonstration positively correlates with its contribution to the models understanding of the test samples resulting in a simple and effective recipe for ICL. Empirically our method yields consistent improvements in both language understanding and generation tasks with different model scales. Further analyses confirm that besides the generality and stability under different circumstances our method provides a unified explanation for the effectiveness of previous methods. Code will be released.
