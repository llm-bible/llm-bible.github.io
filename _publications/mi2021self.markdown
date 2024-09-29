---
layout: publication
title: Self45;training Improves Pre45;training For Few45;shot Learning In Task45;oriented Dialog Systems
authors: Mi Fei, Zhou Wanhao, Cai Fengyu, Kong Lingjing, Huang Minlie, Faltings Boi
conference: "Arxiv"
year: 2021
bibkey: mi2021self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.12589"}
tags: ['BERT', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
As the labeling cost for different modules in task45;oriented dialog (ToD) systems is expensive a major challenge is to train different modules with the least amount of labeled data. Recently large45;scale pre45;trained language models have shown promising results for few45;shot learning in ToD. In this paper we devise a self45;training approach to utilize the abundant unlabeled dialog data to further improve state45;of45;the45;art pre45;trained models in few45;shot learning scenarios for ToD systems. Specifically we propose a self45;training approach that iteratively labels the most confident unlabeled data to train a stronger Student model. Moreover a new text augmentation technique (GradAug) is proposed to better train the Student by replacing non45;crucial tokens using a masked language model. We conduct extensive experiments and present analyses on four downstream tasks in ToD including intent classification dialog state tracking dialog act prediction and response selection. Empirical results demonstrate that the proposed self45;training approach consistently improves state45;of45;the45;art pre45;trained models (BERT ToD45;BERT) when only a small number of labeled data are available.
