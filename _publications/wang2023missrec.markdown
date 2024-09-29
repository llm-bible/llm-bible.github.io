---
layout: publication
title: Missrec Pre-training And Transferring Multi-modal Interest-aware Sequence Representation For Recommendation
authors: Wang Jinpeng, Zeng Ziyun, Wang Yunxiao, Wang Yuting, Lu Xingyu, Li Tianxiang, Yuan Jun, Zhang Rui, Zheng Hai-tao, Xia Shu-tao
conference: "Arxiv"
year: 2023
bibkey: wang2023missrec
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.11175"}
  - {name: "Code", url: "https://github.com/gimpong/MM23-MISSRec"}
tags: ['Fine Tuning', 'Has Code', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
The goal of sequential recommendation (SR) is to predict a users potential interested items based on her/his historical interaction sequences. Most existing sequential recommenders are developed based on ID features which despite their widespread use often underperform with sparse IDs and struggle with the cold-start problem. Besides inconsistent ID mappings hinder the models transferability isolating similar recommendation domains that could have been co-optimized. This paper aims to address these issues by exploring the potential of multi-modal information in learning robust and generalizable sequence representations. We propose MISSRec a multi-modal pre-training and transfer learning framework for SR. On the user side we design a Transformer-based encoder-decoder model where the contextual encoder learns to capture the sequence-level multi-modal user interests while a novel interest-aware decoder is developed to grasp item-modality-interest relations for better sequence representation. On the candidate item side we adopt a dynamic fusion module to produce user-adaptive item representation providing more precise matching between users and items. We pre-train the model with contrastive learning objectives and fine-tune it in an efficient manner. Extensive experiments demonstrate the effectiveness and flexibility of MISSRec promising a practical solution for real-world recommendation scenarios. Data and code are available on urlhttps://github.com/gimpong/MM23-MISSRec}.
