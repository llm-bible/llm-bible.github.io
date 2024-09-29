---
layout: publication
title: Blackvip Black45;box Visual Prompting For Robust Transfer Learning
authors: Oh Changdae, Hwang Hyeji, Lee Hee-young, Lim Yongtaek, Jung Geunyoung, Jung Jiyoung, Choi Hosik, Song Kyungwoo
conference: "Arxiv"
year: 2023
bibkey: oh2023black
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.14773"}
  - {name: "Code", url: "https://github.com/changdaeoh/BlackVIP&#125;"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security', 'Tools']
---
With the surge of large45;scale pre45;trained models (PTMs) fine45;tuning these models to numerous downstream tasks becomes a crucial problem. Consequently parameter efficient transfer learning (PETL) of large models has grasped huge attention. While recent PETL methods showcase impressive performance they rely on optimistic assumptions 1) the entire parameter set of a PTM is available and 2) a sufficiently large memory capacity for the fine45;tuning is equipped. However in most real45;world applications PTMs are served as a black45;box API or proprietary software without explicit parameter accessibility. Besides it is hard to meet a large memory requirement for modern PTMs. In this work we propose black45;box visual prompting (BlackVIP) which efficiently adapts the PTMs without knowledge about model architectures and parameters. BlackVIP has two components; 1) Coordinator and 2) simultaneous perturbation stochastic approximation with gradient correction (SPSA45;GC). The Coordinator designs input45;dependent image45;shaped visual prompts which improves few45;shot adaptation and robustness on distribution/location shift. SPSA45;GC efficiently estimates the gradient of a target model to update Coordinator. Extensive experiments on 16 datasets demonstrate that BlackVIP enables robust adaptation to diverse domains without accessing PTMs parameters with minimal memory requirements. Code url123;https://github.com/changdaeoh/BlackVIP&#125;
