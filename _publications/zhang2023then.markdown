---
layout: publication
title: Prompt Generate Then Cache Cascade Of Foundation Models Makes Strong Few45;shot Learners
authors: Renrui Zhang, Xiangfei Hu, Bohao Li, Siyuan Huang, Hanqiu Deng, Hongsheng Li, Yu Qiao, Peng Gao
conference: "Arxiv"
year: 2023
bibkey: zhang2023then
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2303.02151v1"}
  - {name: "Code", url: "https://github.com/ZrrSkywalker/CaFo"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
Visual recognition in low45;data regimes requires deep neural networks to learn generalized representations from limited training samples. Recently CLIP45;based methods have shown promising few45;shot performance benefited from the contrastive language45;image pre45;training. We then question if the more diverse pre45;training knowledge can be cascaded to further assist few45;shot representation learning. In this paper we propose CaFo a Cascade of Foundation models that incorporates diverse prior knowledge of various pre45;training paradigms for better few45;shot learning. Our CaFo incorporates CLIPs language45;contrastive knowledge DINOs vision45;contrastive knowledge DALL45;Es vision45;generative knowledge and GPT45;3s language45;generative knowledge. Specifically CaFo works by Prompt Generate then Cache. Firstly we leverage GPT45;3 to produce textual inputs for prompting CLIP with rich downstream linguistic semantics. Then we generate synthetic images via DALL45;E to expand the few45;shot training data without any manpower. At last we introduce a learnable cache model to adaptively blend the predictions from CLIP and DINO. By such collaboration CaFo can fully unleash the potential of different pre45;training methods and unify them to perform state45;of45;the45;art for few45;shot classification. Code is available at https://github.com/ZrrSkywalker/CaFo.
