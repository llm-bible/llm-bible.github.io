---
layout: publication
title: Robut A Systematic Study Of Table QA Robustness Against Human45;annotated Adversarial Perturbations
authors: Zhao Yilun, Zhao Chen, Nan Linyong, Qi Zhenting, Zhang Wenlin, Tang Xiangru, Mi Boyu, Radev Dragomir
conference: "Arxiv"
year: 2023
bibkey: zhao2023systematic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.14321"}
  - {name: "Code", url: "https://github.com/yilunzhao/RobuT"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Security', 'Training Techniques']
---
Despite significant progress having been made in question answering on tabular data (Table QA) its unclear whether and to what extent existing Table QA models are robust to task45;specific perturbations e.g. replacing key question entities or shuffling table columns. To systematically study the robustness of Table QA models we propose a benchmark called RobuT which builds upon existing Table QA datasets (WTQ WikiSQL45;Weak and SQA) and includes human45;annotated adversarial perturbations in terms of table header table content and question. Our results indicate that both state45;of45;the45;art Table QA models and large language models (e.g. GPT45;3) with few45;shot learning falter in these adversarial sets. We propose to address this problem by using large language models to generate adversarial examples to enhance training which significantly improves the robustness of Table QA models. Our data and code is publicly available at https://github.com/yilunzhao/RobuT.
