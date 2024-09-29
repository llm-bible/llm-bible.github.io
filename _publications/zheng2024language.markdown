---
layout: publication
title: Dreamlip Language45;image Pre45;training With Long Captions
authors: Zheng Kecheng, Zhang Yifei, Wu Wei, Lu Fan, Ma Shuailei, Jin Xin, Chen Wei, Shen Yujun
conference: "Arxiv"
year: 2024
bibkey: zheng2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.17007"}
tags: ['Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
Language45;image pre45;training largely relies on how precisely and thoroughly a text describes its paired image. In practice however the contents of an image can be so rich that well describing them requires lengthy captions (e.g. with 10 sentences) which are usually missing in existing datasets. Consequently there are currently no clear evidences on whether and how language45;image pre45;training could benefit from long captions. To figure this out we first re45;caption 30M images with detailed descriptions using a pre45;trained Multi45;modality Large Language Model (MLLM) and then study the usage of the resulting captions under a contrastive learning framework. We observe that each sentence within a long caption is very likely to describe the image partially (e.g. an object). Motivated by this we propose to dynamically sample sub45;captions from the text label to construct multiple positive pairs and introduce a grouping loss to match the embeddings of each sub45;caption with its corresponding local image patches in a self45;supervised manner. Experimental results on a wide rage of downstream tasks demonstrate the consistent superiority of our method termed DreamLIP over previous alternatives highlighting its fine45;grained representational capacity. It is noteworthy that on the tasks of image45;text retrieval and semantic segmentation our model trained with 30M image45;text pairs achieves on par or even better performance than CLIP trained with 400M pairs. Project page is available at https://zyf0619sjtu.github.io/dream&#45;lip.
