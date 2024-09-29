---
layout: publication
title: Forgetting Before Learning&#58; Utilizing Parametric Arithmetic For Knowledge Updating In Large Language Models
authors: Ni Shiwen, Chen Dingwei, Li Chengming, Hu Xiping, Xu Ruifeng, Yang Min
conference: "Arxiv"
year: 2023
bibkey: ni2023forgetting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08011"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Recent advancements in Large Language Models (LLMs) have showcased their remarkable capabilities in text understanding and generation. However even stronger LLMs are susceptible to acquiring erroneous or obsolete information from the training corpus. Direct secondary fine-tuning with data containing new knowledge may be ineffective in updating knowledge due to the conflict between old and new knowledge. In this paper we propose a new paradigm for fine-tuning called F-Learning (Forgetting before Learning) which employs parametric arithmetic to facilitate the forgetting of old knowledge and learning of new knowledge. Experimental results on two publicly available datasets demonstrate that our proposed F-Learning can obviously improve the knowledge updating performance of both full fine-tuning and LoRA fine-tuning simultaneously outperforming the existing baselines in most cases. Moreover we have also discovered that forgetting old knowledge by subtracting the parameters of LoRA can yield a similar effect to subtracting the parameters of full fine-tuning and occasionally even surpass it significantly.
