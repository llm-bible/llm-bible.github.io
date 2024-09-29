---
layout: publication
title: Vqattack Transferable Adversarial Attacks On Visual Question Answering Via Pre45;trained Models
authors: Yin Ziyi, Ye Muchao, Zhang Tianrong, Wang Jiaqi, Liu Han, Chen Jinghui, Wang Ting, Ma Fenglong
conference: "Arxiv"
year: 2024
bibkey: yin2024transferable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11083"}
tags: ['Applications', 'Multimodal Models', 'Security', 'Training Techniques']
---
Visual Question Answering (VQA) is a fundamental task in computer vision and natural language process fields. Although the pre45;training amp; finetuning learning paradigm significantly improves the VQA performance the adversarial robustness of such a learning paradigm has not been explored. In this paper we delve into a new problem using a pre45;trained multimodal source model to create adversarial image45;text pairs and then transferring them to attack the target VQA models. Correspondingly we propose a novel VQAttack model which can iteratively generate both image and text perturbations with the designed modules the large language model (LLM)45;enhanced image attack and the cross45;modal joint attack module. At each iteration the LLM45;enhanced image attack module first optimizes the latent representation45;based loss to generate feature45;level image perturbations. Then it incorporates an LLM to further enhance the image perturbations by optimizing the designed masked answer anti45;recovery loss. The cross45;modal joint attack module will be triggered at a specific iteration which updates the image and text perturbations sequentially. Notably the text perturbation updates are based on both the learned gradients in the word embedding space and word synonym45;based substitution. Experimental results on two VQA datasets with five validated models demonstrate the effectiveness of the proposed VQAttack in the transferable attack setting compared with state45;of45;the45;art baselines. This work reveals a significant blind spot in the pre45;training amp; fine45;tuning paradigm on VQA tasks. Source codes will be released.
