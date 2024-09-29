---
layout: publication
title: An Empirical Study Of Training End45;to45;end Vision45;and45;language Transformers
authors: Dou Zi-yi, Xu Yichong, Gan Zhe, Wang Jianfeng, Wang Shuohang, Wang Lijuan, Zhu Chenguang, Zhang Pengchuan, Yuan Lu, Peng Nanyun, Liu Zicheng, Zeng Michael
conference: "Arxiv"
year: 2021
bibkey: dou2021empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.02387"}
  - {name: "Code", url: "https://github.com/zdou0830/METER"}
tags: ['Attention Mechanism', 'BERT', 'Has Code', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Vision45;and45;language (VL) pre45;training has proven to be highly effective on various VL downstream tasks. While recent work has shown that fully transformer45;based VL models can be more efficient than previous region45;feature45;based methods their performance on downstream tasks often degrades significantly. In this paper we present METER a Multimodal End45;to45;end TransformER framework through which we investigate how to design and pre45;train a fully transformer45;based VL model in an end45;to45;end manner. Specifically we dissect the model designs along multiple dimensions vision encoders (e.g. CLIP45;ViT Swin transformer) text encoders (e.g. RoBERTa DeBERTa) multimodal fusion module (e.g. merged attention vs. co45;attention) architectural design (e.g. encoder45;only vs. encoder45;decoder) and pre45;training objectives (e.g. masked image modeling). We conduct comprehensive experiments and provide insights on how to train a performant VL transformer. METER achieves an accuracy of 77.6437; on the VQAv2 test45;std set using only 4M images for pre45;training surpassing the state45;of45;the45;art region45;feature45;based model by 1.0437; and outperforming the previous best fully transformer45;based model by 1.637;. Notably when further scaled up our best VQA model achieves an accuracy of 80.5437;. Code and pre45;trained models are released at https://github.com/zdou0830/METER.
