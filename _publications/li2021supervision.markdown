---
layout: publication
title: Supervision Exists Everywhere A Data Efficient Contrastive Language45;image Pre45;training Paradigm
authors: Li Yangguang, Liang Feng, Zhao Lichen, Cui Yufeng, Ouyang Wanli, Shao Jing, Yu Fengwei, Yan Junjie
conference: "Arxiv"
year: 2021
bibkey: li2021supervision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.05208"}
  - {name: "Code", url: "https://github.com/Sense&#45;GVT/DeCLIP"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Tools', 'Training Techniques']
---
Recently large45;scale Contrastive Language45;Image Pre45;training (CLIP) has attracted unprecedented attention for its impressive zero45;shot recognition ability and excellent transferability to downstream tasks. However CLIP is quite data45;hungry and requires 400M image45;text pairs for pre45;training thereby restricting its adoption. This work proposes a novel training paradigm Data efficient CLIP (DeCLIP) to alleviate this limitation. We demonstrate that by carefully utilizing the widespread supervision among the image45;text pairs our De45;CLIP can learn generic visual features more efficiently. Instead of using the single image45;text contrastive supervision we fully exploit data potential through the use of (1) self45;supervision within each modality; (2) multi45;view supervision across modalities; (3) nearest45;neighbor supervision from other similar pairs. Benefiting from intrinsic supervision our DeCLIP45;ResNet50 can achieve 60.437; zero45;shot top1 accuracy on ImageNet which is 0.837; above the CLIP45;ResNet50 while using 7.1 x fewer data. Our DeCLIP45;ResNet50 outperforms its counterpart in 8 out of 11 visual datasets when transferred to downstream tasks. Moreover Scaling up the model and computing also works well in our framework.Our code dataset and models are released at https://github.com/Sense&#45;GVT/DeCLIP
