---
layout: publication
title: Expedited Training Of Visual Conditioned Language Generation Via Redundancy Reduction
authors: Jian Yiren, Liu Tingkai, Tao Yunzhe, Zhang Chunhui, Vosoughi Soroush, Yang Hongxia
conference: "Arxiv"
year: 2023
bibkey: jian2023expedited
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03291"}
  - {name: "Code", url: "https://github.com/yiren&#45;jian/EVLGen&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'Merging', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
In this paper we introduce text123;EVL125;95;123;text123;Gen125;125; a streamlined framework designed for the pre45;training of visually conditioned language generation models with high computational demands utilizing frozen pre45;trained large language models (LLMs). The conventional approach in vision45;language pre45;training (VLP) typically involves a two45;stage optimization process an initial resource45;intensive phase dedicated to general45;purpose vision45;language representation learning focused on extracting and consolidating relevant visual features. This is followed by a subsequent phase that emphasizes end45;to45;end alignment between visual and linguistic modalities. Our novel one45;stage single45;loss framework bypasses the computationally demanding first training stage by gradually merging similar visual tokens during training while avoiding model collapse caused by single45;stage training of BLIP45;2 type models. The gradual merging process effectively condenses visual information while preserving semantic richness resulting in rapid convergence without compromising performance. Our experimental findings demonstrate that our approach accelerates the training of vision45;language models by a factor of 5 without a noticeable impact on overall performance. Furthermore we illustrate that our models significantly narrow the performance gap to current vision45;language models using only 1/10 of the data. Finally we showcase how our image45;text models can seamlessly adapt to video45;conditioned language generation tasks through novel soft attentive temporal token contextualizing modules. Code is available at url123;https://github.com/yiren&#45;jian/EVLGen&#125;.
