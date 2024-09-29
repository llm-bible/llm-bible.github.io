---
layout: publication
title: Image Re45;identification Where Self45;supervision Meets Vision45;language Learning
authors: Wang Bin, Liang Yuying, Cai Lei, Huang Huakun, Zeng Huanqiang
conference: "Arxiv"
year: 2024
bibkey: wang2024image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20647"}
  - {name: "Code", url: "https://github.com/BinWangGzhu/SVLL&#45;ReID"}
tags: ['Has Code', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Recently large45;scale vision45;language pre45;trained models like CLIP have shown impressive performance in image re45;identification (ReID). In this work we explore whether self45;supervision can aid in the use of CLIP for image ReID tasks. Specifically we propose SVLL45;ReID the first attempt to integrate self45;supervision and pre45;trained CLIP via two training stages to facilitate the image ReID. We observe that 1) incorporating language self45;supervision in the first training stage can make the learnable text prompts more distinguishable and 2) incorporating vision self45;supervision in the second training stage can make the image features learned by the image encoder more discriminative. These observations imply that 1) the text prompt learning in the first stage can benefit from the language self45;supervision and 2) the image feature learning in the second stage can benefit from the vision self45;supervision. These benefits jointly facilitate the performance gain of the proposed SVLL45;ReID. By conducting experiments on six image ReID benchmark datasets without any concrete text labels we find that the proposed SVLL45;ReID achieves the overall best performances compared with state45;of45;the45;arts. Codes will be publicly available at https://github.com/BinWangGzhu/SVLL&#45;ReID.
