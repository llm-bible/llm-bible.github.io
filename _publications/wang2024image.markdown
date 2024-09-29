---
layout: publication
title: Image Re-identification&#58; Where Self-supervision Meets Vision-language Learning
authors: Wang Bin, Liang Yuying, Cai Lei, Huang Huakun, Zeng Huanqiang
conference: "Arxiv"
year: 2024
bibkey: wang2024image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20647"}
  - {name: "Code", url: "https://github.com/BinWangGzhu/SVLL-ReID"}
tags: ['Has Code', 'Multimodal Models', 'Prompting', 'Training Techniques']
---
Recently large-scale vision-language pre-trained models like CLIP have shown impressive performance in image re-identification (ReID). In this work we explore whether self-supervision can aid in the use of CLIP for image ReID tasks. Specifically we propose SVLL-ReID the first attempt to integrate self-supervision and pre-trained CLIP via two training stages to facilitate the image ReID. We observe that 1) incorporating language self-supervision in the first training stage can make the learnable text prompts more distinguishable and 2) incorporating vision self-supervision in the second training stage can make the image features learned by the image encoder more discriminative. These observations imply that 1) the text prompt learning in the first stage can benefit from the language self-supervision and 2) the image feature learning in the second stage can benefit from the vision self-supervision. These benefits jointly facilitate the performance gain of the proposed SVLL-ReID. By conducting experiments on six image ReID benchmark datasets without any concrete text labels we find that the proposed SVLL-ReID achieves the overall best performances compared with state-of-the-arts. Codes will be publicly available at https://github.com/BinWangGzhu/SVLL-ReID."
