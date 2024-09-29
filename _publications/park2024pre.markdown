---
layout: publication
title: Pre45;trained Vision And Language Transformers Are Few45;shot Incremental Learners
authors: Park Keon-hee, Song Kyungwoo, Park Gyeong-moon
conference: "Arxiv"
year: 2024
bibkey: park2024pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02117"}
  - {name: "Code", url: "https://github.com/KHU&#45;AGI/PriViLege"}
tags: ['Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Transformer']
---
Few45;Shot Class Incremental Learning (FSCIL) is a task that requires a model to learn new classes incrementally without forgetting when only a few samples for each class are given. FSCIL encounters two significant challenges catastrophic forgetting and overfitting and these challenges have driven prior studies to primarily rely on shallow models such as ResNet45;18. Even though their limited capacity can mitigate both forgetting and overfitting issues it leads to inadequate knowledge transfer during few45;shot incremental sessions. In this paper we argue that large models such as vision and language transformers pre45;trained on large datasets can be excellent few45;shot incremental learners. To this end we propose a novel FSCIL framework called PriViLege Pre45;trained Vision and Language transformers with prompting functions and knowledge distillation. Our framework effectively addresses the challenges of catastrophic forgetting and overfitting in large models through new pre45;trained knowledge tuning (PKT) and two losses entropy45;based divergence loss and semantic knowledge distillation loss. Experimental results show that the proposed PriViLege significantly outperforms the existing state45;of45;the45;art methods with a large margin e.g. +9.3837; in CUB200 +20.5837; in CIFAR45;100 and +13.3637; in miniImageNet. Our implementation code is available at https://github.com/KHU&#45;AGI/PriViLege.
