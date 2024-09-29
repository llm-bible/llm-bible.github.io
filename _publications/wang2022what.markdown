---
layout: publication
title: What Language Model Architecture And Pretraining Objective Work Best For Zero45;shot Generalization
authors: Wang Thomas, Roberts Adam, Hesslow Daniel, Scao Teven Le, Chung Hyung Won, Beltagy Iz, Launay Julien, Raffel Colin
conference: "Arxiv"
year: 2022
bibkey: wang2022what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.05832"}
  - {name: "Code", url: "https://github.com/bigscience&#45;workshop/architecture&#45;objective"}
tags: ['BERT', 'GPT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques', 'Transformer']
---
Large pretrained Transformer language models have been shown to exhibit zero45;shot generalization i.e. they can perform a wide variety of tasks that they were not explicitly trained on. However the architectures and pretraining objectives used across state45;of45;the45;art models differ significantly and there has been limited systematic comparison of these factors. In this work we present a large45;scale evaluation of modeling choices and their impact on zero45;shot generalization. In particular we focus on text45;to45;text models and experiment with three model architectures (causal/non45;causal decoder45;only and encoder45;decoder) trained with two different pretraining objectives (autoregressive and masked language modeling) and evaluated with and without multitask prompted finetuning. We train models with over 5 billion parameters for more than 170 billion tokens thereby increasing the likelihood that our conclusions will transfer to even larger scales. Our experiments show that causal decoder45;only models trained on an autoregressive language modeling objective exhibit the strongest zero45;shot generalization after purely unsupervised pretraining. However models with non45;causal visibility on their input trained with a masked language modeling objective followed by multitask finetuning perform the best among our experiments. We therefore consider the adaptation of pretrained models across architectures and objectives. We find that pretrained non45;causal decoder models can be adapted into performant generative causal decoder models using autoregressive language modeling as a downstream task. Furthermore we find that pretrained causal decoder models can be efficiently adapted into non45;causal decoder models ultimately achieving competitive performance after multitask finetuning. Code and checkpoints are available at https://github.com/bigscience&#45;workshop/architecture&#45;objective.
