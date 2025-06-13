---
layout: publication
title: 'Topicvd: A Topic-based Dataset Of Video-guided Multimodal Machine Translation For Documentaries'
authors: Jinze Lv, Jian Chen, Zi Long, Xianghua Fu, Yin Chen
conference: "Arxiv"
year: 2025
bibkey: lv2025topic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05714"}
  - {name: "Code", url: "https://github.com/JinzeLv/TopicVD"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Fine-Tuning', 'Has Code', 'Applications', 'Attention Mechanism']
---
Most existing multimodal machine translation (MMT) datasets are predominantly composed of static images or short video clips, lacking extensive video data across diverse domains and topics. As a result, they fail to meet the demands of real-world MMT tasks, such as documentary translation. In this study, we developed TopicVD, a topic-based dataset for video-supported multimodal machine translation of documentaries, aiming to advance research in this field. We collected video-subtitle pairs from documentaries and categorized them into eight topics, such as economy and nature, to facilitate research on domain adaptation in video-guided MMT. Additionally, we preserved their contextual information to support research on leveraging the global context of documentaries in video-guided MMT. To better capture the shared semantics between text and video, we propose an MMT model based on a cross-modal bidirectional attention module. Extensive experiments on the TopicVD dataset demonstrate that visual information consistently improves the performance of the NMT model in documentary translation. However, the MMT model's performance significantly declines in out-of-domain scenarios, highlighting the need for effective domain adaptation methods. Additionally, experiments demonstrate that global context can effectively improve translation performance. % Dataset and our implementations are available at https://github.com/JinzeLv/TopicVD
