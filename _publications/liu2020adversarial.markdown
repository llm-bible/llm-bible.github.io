---
layout: publication
title: Adversarial Training For Large Neural Language Models
authors: Liu Xiaodong, Cheng Hao, He Pengcheng, Chen Weizhu, Wang Yu, Poon Hoifung, Gao Jianfeng
conference: "Arxiv"
year: 2020
bibkey: liu2020adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.08994"}
  - {name: "Code", url: "https://github.com/namisan/mt&#45;dnn"}
tags: ['BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Security', 'Survey Paper', 'Training Techniques']
---
Generalization and robustness are both key desiderata for designing machine learning methods. Adversarial training can enhance robustness but past work often finds it hurts generalization. In natural language processing (NLP) pre45;training large neural language models such as BERT have demonstrated impressive gain in generalization for a variety of tasks with further improvement from adversarial fine45;tuning. However these models are still vulnerable to adversarial attacks. In this paper we show that adversarial pre45;training can improve both generalization and robustness. We propose a general algorithm ALUM (Adversarial training for large neural LangUage Models) which regularizes the training objective by applying perturbations in the embedding space that maximizes the adversarial loss. We present the first comprehensive study of adversarial training in all stages including pre45;training from scratch continual pre45;training on a well45;trained model and task45;specific fine45;tuning. ALUM obtains substantial gains over BERT on a wide range of NLP tasks in both regular and adversarial scenarios. Even for models that have been well trained on extremely large text corpora such as RoBERTa ALUM can still produce significant gains from continual pre45;training whereas conventional non45;adversarial methods can not. ALUM can be further combined with task45;specific fine45;tuning to attain additional gains. The ALUM code is publicly available at https://github.com/namisan/mt&#45;dnn.
