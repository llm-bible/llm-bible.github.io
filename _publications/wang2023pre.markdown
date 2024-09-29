---
layout: publication
title: Missrec Pre45;training And Transferring Multi45;modal Interest45;aware Sequence Representation For Recommendation
authors: Wang Jinpeng, Zeng Ziyun, Wang Yunxiao, Wang Yuting, Lu Xingyu, Li Tianxiang, Yuan Jun, Zhang Rui, Zheng Hai-tao, Xia Shu-tao
conference: "Arxiv"
year: 2023
bibkey: wang2023pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11175"}
  - {name: "Code", url: "https://github.com/gimpong/MM23&#45;MISSRec&#125;"}
tags: ['Fine Tuning', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The goal of sequential recommendation (SR) is to predict a users potential interested items based on her/his historical interaction sequences. Most existing sequential recommenders are developed based on ID features which despite their widespread use often underperform with sparse IDs and struggle with the cold45;start problem. Besides inconsistent ID mappings hinder the models transferability isolating similar recommendation domains that could have been co45;optimized. This paper aims to address these issues by exploring the potential of multi45;modal information in learning robust and generalizable sequence representations. We propose MISSRec a multi45;modal pre45;training and transfer learning framework for SR. On the user side we design a Transformer45;based encoder45;decoder model where the contextual encoder learns to capture the sequence45;level multi45;modal user interests while a novel interest45;aware decoder is developed to grasp item45;modality45;interest relations for better sequence representation. On the candidate item side we adopt a dynamic fusion module to produce user45;adaptive item representation providing more precise matching between users and items. We pre45;train the model with contrastive learning objectives and fine45;tune it in an efficient manner. Extensive experiments demonstrate the effectiveness and flexibility of MISSRec promising a practical solution for real45;world recommendation scenarios. Data and code are available on url123;https://github.com/gimpong/MM23&#45;MISSRec&#125;.
