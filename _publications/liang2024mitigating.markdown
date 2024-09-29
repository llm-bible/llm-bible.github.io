---
layout: publication
title: Mitigating Hallucination In Visual-language Models Via Re-balancing Contrastive Decoding
authors: Liang Xiaoyu, Yu Jiayuan, Mu Lianrui, Zhuang Jiedong, Hu Jiaqi, Yang Yuchen, Ye Jiangnan, Lu Lu, Chen Jian, Hu Haoji
conference: "Arxiv"
year: 2024
bibkey: liang2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06485"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Multimodal Models', 'Transformer']
---
Although Visual-Language Models (VLMs) have shown impressive capabilities in tasks like visual question answering and image captioning they still struggle with hallucinations. Analysis of attention distribution in these models shows that VLMs tend to processing textual tokens rather than visual tokens. This imbalance of attention distribution causes VLMs to favor textual knowledge in the case of multimodal knowledge conflicts resulting in differences from the image information. In this paper we propose Re-Balancing Contrastive Decoding (RBD) method which employs textual and visual branches to recalibrate attention distribution in VLMs. Specifically the textual branch injects image noise to stimulate the models dependency on text thereby reducing textual bias. Concurrently the visual branch focuses on the selection of significant tokens refining the attention mechanism to highlight the primary subject. This dual-branch strategy enables the RBD method to diminish textual bias while enhancing visual information. Experimental results demonstrate that our method RBD outperforms the existing methods by the CHAIR and POPE metrics mitigate hallucinations without reducing the models general capabilities.
