---
layout: publication
title: E2E45;VLP End45;to45;end Vision45;language Pre45;training Enhanced By Visual Learning
authors: Xu Haiyang, Yan Ming, Li Chenliang, Bi Bin, Huang Songfang, Xiao Wenming, Huang Fei
conference: "Arxiv"
year: 2021
bibkey: xu2021end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.01804"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Vision45;language pre45;training (VLP) on large45;scale image45;text pairs has achieved huge success for the cross45;modal downstream tasks. The most existing pre45;training methods mainly adopt a two45;step training procedure which firstly employs a pre45;trained object detector to extract region45;based visual features then concatenates the image representation and text embedding as the input of Transformer to train. However these methods face problems of using task45;specific visual representation of the specific object detector for generic cross45;modal understanding and the computation inefficiency of two45;stage pipeline. In this paper we propose the first end45;to45;end vision45;language pre45;trained model for both V+L understanding and generation namely E2E45;VLP where we build a unified Transformer framework to jointly learn visual representation and semantic alignments between image and text. We incorporate the tasks of object detection and image captioning into pre45;training with a unified Transformer encoder45;decoder architecture for enhancing visual learning. An extensive set of experiments have been conducted on well45;established vision45;language downstream tasks to demonstrate the effectiveness of this novel VLP paradigm.
