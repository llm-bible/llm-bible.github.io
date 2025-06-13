---
layout: publication
title: 'Quantification Of Large Language Model Distillation'
authors: Sunbowen Lee, Junting Zhou, Chang Ao, Kaige Li, Xinrun Du, Sirui He, Haihong Wu, Tianci Liu, Jiaheng Liu, Hamid Alinejad-rokny, Min Yang, Yitao Liang, Zhoufutu Wen, Shiwen Ni
conference: "Arxiv"
year: 2025
bibkey: lee2025quantification
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12619"}
  - {name: "Code", url: "https://github.com/Aegis1863/LLMs-Distillation-Quantification"}
tags: ['Responsible AI', 'Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability', 'Security', 'Has Code', 'Distillation']
---
Model distillation is a fundamental technique in building large language
models (LLMs), transferring knowledge from a teacher model to a student model.
However, distillation can lead to model homogenization, reducing diversity
among models and impairing their ability to robustly handle complex or novel
tasks. These limitations underscore the need to systematically quantify the
distillation process and its impact. In this work, we propose a framework to
evaluate and quantify model distillation. Our method addresses two key aspects:
(1) Identifying identity cognition contradictions to assess discrepancies in
how models perceive and represent identity-related information, and (2)
Analyzing multi-granularity response similarities across models to measure the
extent of homogenization. Experimental results demonstrate two key insights:
(1) Well-known closed-source and open-source LLMs usually exhibit high
distillation degrees, except for Claude, Doubao, and Gemini. (2) Base LLMs show
higher distillation degrees compared to aligned LLMs. By offering a systematic
approach to improve the transparency of LLM data distillation, we call for LLMs
with more independent development and more transparent technical reports to
improve LLMs' robustness and safety. The code and data are available under
https://github.com/Aegis1863/LLMs-Distillation-Quantification.
