---
layout: publication
title: Coda Constrained Generation Based Data Augmentation For Low45;resource NLP
authors: Evuru Chandra Kiran Reddy, Ghosh Sreyan, Kumar Sonal, S Ramaneswaran, Tyagi Utkarsh, Manocha Dinesh
conference: "Arxiv"
year: 2024
bibkey: evuru2024constrained
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00415"}
  - {name: "Code", url: "https://github.com/Sreyan88/CoDa"}
tags: ['Ethics And Bias', 'Has Code', 'Prompting', 'Tools', 'Training Techniques']
---
We present CoDa (Constrained Generation based Data Augmentation) a controllable effective and training45;free data augmentation technique for low45;resource (data45;scarce) NLP. Our approach is based on prompting off45;the45;shelf instruction45;following Large Language Models (LLMs) for generating text that satisfies a set of constraints. Precisely we extract a set of simple constraints from every instance in the low45;resource dataset and verbalize them to prompt an LLM to generate novel and diverse training instances. Our findings reveal that synthetic data that follows simple constraints in the downstream dataset act as highly effective augmentations and CoDa can achieve this without intricate decoding45;time constrained generation techniques or fine45;tuning with complex algorithms that eventually make the model biased toward the small number of training instances. Additionally CoDa is the first framework that provides users explicit control over the augmentation generation process thereby also allowing easy adaptation to several domains. We demonstrate the effectiveness of CoDa across 11 datasets spanning 3 tasks and 3 low45;resource settings. CoDa outperforms all our baselines qualitatively and quantitatively with improvements of 0.1237;45;7.1937;. Code is available here https://github.com/Sreyan88/CoDa
