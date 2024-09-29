---
layout: publication
title: Lyrics: Boosting Fine-grained Language-vision Alignment And Comprehension Via Semantic-aware Visual Objects
authors: Lu Junyu, Zhang Dixiang, Zhang Songxin, Xie Zejian, Song Zhuoyang, Lin Cong, Zhang Jiaxing, Jing Bingyi, Zhang Pingjian
conference: "Arxiv"
year: 2023
bibkey: lu2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05278"}
tags: ['Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large Vision Language Models (LVLMs) have demonstrated impressive zero-shot capabilities in various vision-language dialogue scenarios. However the absence of fine-grained visual object detection hinders the model from understanding the details of images leading to irreparable visual hallucinations and factual errors. In this paper we propose Lyrics a novel multi-modal pre-training and instruction fine-tuning paradigm that bootstraps vision-language alignment from fine-grained cross-modal collaboration. Building on the foundation of BLIP-2 Lyrics infuses local visual features extracted from a visual refiner that includes image tagging object detection and semantic segmentation modules into the Querying Transformer while on the text side the language inputs equip the boundary boxes and tags derived from the visual refiner. We further introduce a two-stage training scheme in which the pre-training stage bridges the modality gap through explicit and comprehensive vision-language alignment targets. During the instruction fine-tuning stage we introduce semantic-aware visual feature extraction a crucial method that enables the model to extract informative features from concrete visual objects. Our approach achieves robust performance on 13 datasets across various vision-language tasks and demonstrates promising multi-modal understanding perception and conversation capabilities in 11 scenario-based benchmark toolkits.
