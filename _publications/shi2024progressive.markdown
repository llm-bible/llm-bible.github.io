---
layout: publication
title: Profuser: Progressive Fusion Of Large Language Models
authors: Shi Tianyuan, Wan Fanqi, Huang Canbin, Quan Xiaojun, Li Chenliang, Yan Ming, Zhang Ji
conference: "Arxiv"
year: 2024
bibkey: shi2024progressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04998"}
tags: ['Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
While fusing the capacities and advantages of various large language models (LLMs) offers a pathway to construct more powerful and versatile models a fundamental challenge is to properly select advantageous model during the training. Existing fusion methods primarily focus on the training mode that uses cross entropy on ground truth in a teacher-forcing setup to measure a models advantage which may provide limited insight towards model advantage. In this paper we introduce a novel approach that enhances the fusion process by incorporating both the training and inference modes. Our method evaluates model advantage not only through cross entropy during training but also by considering inference outputs providing a more comprehensive assessment. To combine the two modes effectively we introduce ProFuser to progressively transition from inference mode to training mode. To validate ProFusers effectiveness we fused three models including vicuna-7b-v1.5 Llama-2-7b-chat and mpt-7b-8k-chat and demonstrated the improved performance in knowledge reasoning and safety compared to baseline methods.
