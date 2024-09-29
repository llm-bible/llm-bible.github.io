---
layout: publication
title: Lyrics Boosting Fine45;grained Language45;vision Alignment And Comprehension Via Semantic45;aware Visual Objects
authors: Lu Junyu, Zhang Dixiang, Zhang Songxin, Xie Zejian, Song Zhuoyang, Lin Cong, Zhang Jiaxing, Jing Bingyi, Zhang Pingjian
conference: "Arxiv"
year: 2023
bibkey: lu2023boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05278"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Large Vision Language Models (LVLMs) have demonstrated impressive zero45;shot capabilities in various vision45;language dialogue scenarios. However the absence of fine45;grained visual object detection hinders the model from understanding the details of images leading to irreparable visual hallucinations and factual errors. In this paper we propose Lyrics a novel multi45;modal pre45;training and instruction fine45;tuning paradigm that bootstraps vision45;language alignment from fine45;grained cross45;modal collaboration. Building on the foundation of BLIP45;2 Lyrics infuses local visual features extracted from a visual refiner that includes image tagging object detection and semantic segmentation modules into the Querying Transformer while on the text side the language inputs equip the boundary boxes and tags derived from the visual refiner. We further introduce a two45;stage training scheme in which the pre45;training stage bridges the modality gap through explicit and comprehensive vision45;language alignment targets. During the instruction fine45;tuning stage we introduce semantic45;aware visual feature extraction a crucial method that enables the model to extract informative features from concrete visual objects. Our approach achieves robust performance on 13 datasets across various vision45;language tasks and demonstrates promising multi45;modal understanding perception and conversation capabilities in 11 scenario45;based benchmark toolkits.
