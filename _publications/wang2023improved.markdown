---
layout: publication
title: Improved Visual Fine45;tuning With Natural Language Supervision
authors: Wang Junyang, Xu Yuanhong, Hu Juhua, Yan Ming, Sang Jitao, Qian Qi
conference: "Arxiv"
year: 2023
bibkey: wang2023improved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.01489"}
  - {name: "Code", url: "https://github.com/idstcv/TeS&#125;"}
tags: ['Attention Mechanism', 'BERT', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Fine45;tuning a visual pre45;trained model can leverage the semantic information from large45;scale pre45;training data and mitigate the over45;fitting problem on downstream vision tasks with limited training examples. While the problem of catastrophic forgetting in pre45;trained backbone has been extensively studied for fine45;tuning its potential bias from the corresponding pre45;training task and data attracts less attention. In this work we investigate this problem by demonstrating that the obtained classifier after fine45;tuning will be close to that induced by the pre45;trained model. To reduce the bias in the classifier effectively we introduce a reference distribution obtained from a fixed text classifier which can help regularize the learned vision classifier. The proposed method Text Supervised fine45;tuning (TeS) is evaluated with diverse pre45;trained vision models including ResNet and ViT and text encoders including BERT and CLIP on 11 downstream tasks. The consistent improvement with a clear margin over distinct scenarios confirms the effectiveness of our proposal. Code is available at url123;https://github.com/idstcv/TeS&#125;.
