---
layout: publication
title: 'Actions Speak Louder Than Words: Trillion-parameter Sequential Transducers For Generative Recommendations'
authors: Zhai Jiaqi, Liao Lucy, Liu Xing, Wang Yueming, Li Rui, Cao Xuan, Gao Leon, Gong Zhaojie, Gu Fangda, He Michael, Lu Yinghai, Shi Yu
conference: "Arxiv"
year: 2024
bibkey: zhai2024actions
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17152"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
"Large-scale recommendation systems are characterized by their reliance on high cardinality, heterogeneous features and the need to handle tens of billions of user actions on a daily basis. Despite being trained on huge volume of data with thousands of features, most Deep Learning Recommendation Models (DLRMs) in industry fail to scale with compute. Inspired by success achieved by Transformers in language and vision domains, we revisit fundamental design choices in recommendation systems. We reformulate recommendation problems as sequential transduction tasks within a generative modeling framework (Generative Recommenders), and propose a new architecture, HSTU, designed for high cardinality, non-stationary streaming recommendation data. HSTU outperforms baselines over synthetic and public datasets by up to 65.8&#37; in NDCG, and is 5.3x to 15.2x faster than FlashAttention2-based Transformers on 8192 length sequences. HSTU-based Generative Recommenders, with 1.5 trillion parameters, improve metrics in online A/B tests by 12.4&#37; and have been deployed on multiple surfaces of a large internet platform with billions of users. More importantly, the model quality of Generative Recommenders empirically scales as a power-law of training compute across three orders of magnitude, up to GPT-3/LLaMa-2 scale, which reduces carbon footprint needed for future model developments, and further paves the way for the first foundational models in recommendations."
