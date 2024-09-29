---
layout: publication
title: Dual Modality Prompt Tuning For Vision45;language Pre45;trained Model
authors: Xing Yinghui, Wu Qirui, Cheng De, Zhang Shizhou, Liang Guoqiang, Wang Peng, Zhang Yanning
conference: "IEEE Transactions on Multimedia"
year: 2022
bibkey: xing2022dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.08340"}
  - {name: "Code", url: "https://github.com/fanrena/DPT"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Prompting', 'Training Techniques']
---
With the emergence of large pre45;trained vison45;language model like CLIP transferable representations can be adapted to a wide range of downstream tasks via prompt tuning. Prompt tuning tries to probe the beneficial information for downstream tasks from the general knowledge stored in the pre45;trained model. A recently proposed method named Context Optimization (CoOp) introduces a set of learnable vectors as text prompt from the language side. However tuning the text prompt alone can only adjust the synthesized classifier while the computed visual features of the image encoder can not be affected thus leading to sub45;optimal solutions. In this paper we propose a novel Dual45;modality Prompt Tuning (DPT) paradigm through learning text and visual prompts simultaneously. To make the final image feature concentrate more on the target visual concept a Class45;Aware Visual Prompt Tuning (CAVPT) scheme is further proposed in our DPT where the class45;aware visual prompt is generated dynamically by performing the cross attention between text prompts features and image patch token embeddings to encode both the downstream task45;related information and visual instance information. Extensive experimental results on 11 datasets demonstrate the effectiveness and generalization ability of the proposed method. Our code is available in https://github.com/fanrena/DPT.
