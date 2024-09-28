---
layout: publication
title: Multimodal Incremental Transformer with Visual Grounding for Visual Dialogue Generation
authors: Chen Feilong, Meng Fandong, Chen Xiuyi, Li Peng, Zhou Jie
conference: "Arxiv"
year: 2021
bibkey: chen2021multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.08478"}
tags: ['ARXIV', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Transformer']
---
Visual dialogue is a challenging task since it needs to answer a series of coherent questions on the basis of understanding the visual environment. Previous studies focus on the implicit exploration of multimodal co-reference by implicitly attending to spatial image features or object-level image features but neglect the importance of locating the objects explicitly in the visual content which is associated with entities in the textual content. Therefore in this paper we propose a bf Multimodal bf Incremental bf Transformer with bf Visual bf Grounding named MITVG which consists of two key parts visual grounding and multimodal incremental transformer. Visual grounding aims to explicitly locate related objects in the image guided by textual entities which helps the model exclude the visual content that does not need attention. On the basis of visual grounding the multimodal incremental transformer encodes the multi-turn dialogue history combined with visual scene step by step according to the order of the dialogue and then generates a contextually and visually coherent response. Experimental results on the VisDial v0.9 and v1.0 datasets demonstrate the superiority of the proposed model which achieves comparable performance.
