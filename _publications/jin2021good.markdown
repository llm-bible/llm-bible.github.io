---
layout: publication
title: A Good Prompt Is Worth Millions Of Parameters Low45;resource Prompt45;based Learning For Vision45;language Models
authors: Jin Woojeong, Cheng Yu, Shen Yelong, Chen Weizhu, Ren Xiang
conference: "Arxiv"
year: 2021
bibkey: jin2021good
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08484"}
  - {name: "Code", url: "https://github.com/woojeongjin/FewVLM&#125;"}
tags: ['Applications', 'BERT', 'Has Code', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Large pre45;trained vision45;language (VL) models can learn a new task with a handful of examples and generalize to a new task without fine45;tuning. However these VL models are hard to deploy for real45;world applications due to their impractically huge sizes and slow inference speed. To solve this limitation we study prompt45;based low45;resource learning of VL tasks with our proposed method FewVLM relatively smaller than recent few45;shot learners. For FewVLM we pre45;train a sequence45;to45;sequence transformer model with prefix language modeling (PrefixLM) and masked language modeling (MaskedLM). Furthermore we analyze the effect of diverse prompts for few45;shot tasks. Experimental results on VQA show that FewVLM with prompt45;based learning outperforms Frozen which is 31x larger than FewVLM by 18.237; point and achieves comparable results to a 246x larger model PICa. In our analysis we observe that (1) prompts significantly affect zero45;shot performance but marginally affect few45;shot performance (2) models with noisy prompts learn as quickly as hand45;crafted prompts given larger training data and (3) MaskedLM helps VQA tasks while PrefixLM boosts captioning performance. Our code is publicly available at url123;https://github.com/woojeongjin/FewVLM&#125;
