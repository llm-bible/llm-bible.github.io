---
layout: publication
title: Improving Question Generation With Multi45;level Content Planning
authors: Xia Zehua, Gou Qi, Yu Bowen, Yu Haiyang, Huang Fei, Li Yongbin, Nguyen Cam-tu
conference: "Arxiv"
year: 2023
bibkey: xia2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.13512"}
  - {name: "Code", url: "https://github.com/zeaver/MultiFactor"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
This paper addresses the problem of generating questions from a given context and an answer specifically focusing on questions that require multi45;hop reasoning across an extended context. Previous studies have suggested that key phrase selection is essential for question generation (QG) yet it is still challenging to connect such disjointed phrases into meaningful questions particularly for long context. To mitigate this issue we propose MultiFactor a novel QG framework based on multi45;level content planning. Specifically MultiFactor includes two components FA45;model which simultaneously selects key phrases and generates full answers and Q45;model which takes the generated full answer as an additional input to generate questions. Here full answer generation is introduced to connect the short answer with the selected key phrases thus forming an answer45;aware summary to facilitate QG. Both FA45;model and Q45;model are formalized as simple45;yet45;effective Phrase45;Enhanced Transformers our joint model for phrase selection and text generation. Experimental results show that our method outperforms strong baselines on two popular QG datasets. Our code is available at https://github.com/zeaver/MultiFactor.
