---
layout: publication
title: 'SAPT: A Shared Attention Framework For Parameter-efficient Continual Learning Of Large Language Models'
authors: Zhao Weixiang, Wang Shilong, Hu Yulin, Zhao Yanyan, Qin Bing, Zhang Xuanyu, Yang Qing, Xu Dongliang, Che Wanxiang
conference: "Arxiv"
year: 2024
bibkey: zhao2024shared
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.08295"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
The continual learning (CL) ability is vital for deploying large language models (LLMs) in the dynamic world. Existing methods devise the learning module to acquire task-specific knowledge with parameter-efficient tuning (PET) block and the selection module to pick out the corresponding one for the testing input aiming at handling the challenges of catastrophic forgetting and knowledge transfer in CL. However these methods tend to address only one of the challenges ignoring the potential of aligning the two modules to effectively address catastrophic forgetting and knowledge transfer simultaneously. To this end we propose a novel Shared Attention Framework (SAPT) to align the PET learning and selection via the Shared Attentive Learning amp; Selection module. Extensive Experiments on two CL benchmarks demonstrate the superiority of SAPT. Moreover SAPT consistently demonstrates its superiority when we scale it to different model sizes (from 770M to 13B) different model architectures (T5 and LLaMA-2) and unseen tasks.
