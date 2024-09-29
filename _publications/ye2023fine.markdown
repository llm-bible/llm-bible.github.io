---
layout: publication
title: FLASK Fine45;grained Language Model Evaluation Based On Alignment Skill Sets
authors: Ye Seonghyeon, Kim Doyoung, Kim Sungdong, Hwang Hyeonbin, Kim Seungone, Jo Yongrae, Thorne James, Kim Juho, Seo Minjoon
conference: "Arxiv"
year: 2023
bibkey: ye2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.10928"}
  - {name: "Code", url: "https://github.com/kaistAI/FLASK"}
tags: ['Has Code', 'Interpretability And Explainability', 'Pretraining Methods']
---
Evaluation of Large Language Models (LLMs) is challenging because instruction45;following necessitates alignment with human values and the required set of skills varies depending on the instruction. However previous studies have mainly focused on coarse45;grained evaluation (i.e. overall preference45;based evaluation) which limits interpretability since it does not consider the nature of user instructions that require instance45;wise skill composition. In this paper we introduce FLASK (Fine45;grained Language Model Evaluation based on Alignment Skill Sets) a fine45;grained evaluation protocol for both human45;based and model45;based evaluation which decomposes coarse45;level scoring to a skill set45;level scoring for each instruction. We experimentally observe that the fine45;graininess of evaluation is crucial for attaining a holistic view of model performance and increasing the reliability of the evaluation. Using FLASK we compare multiple open45;source and proprietary LLMs and observe a high correlation between model45;based and human45;based evaluations. We publicly release the evaluation data and code implementation at https://github.com/kaistAI/FLASK.
