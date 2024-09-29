---
layout: publication
title: Veclip Improving CLIP Training Via Visual45;enriched Captions
authors: Lai Zhengfeng, Zhang Haotian, Zhang Bowen, Wu Wentao, Bai Haoping, Timofeev Aleksei, Du Xianzhi, Gan Zhe, Shan Jiulong, Chuah Chen-nee, Yang Yinfei, Cao Meng
conference: "Arxiv"
year: 2023
bibkey: lai2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07699"}
  - {name: "Code", url: "https://github.com/apple/ml&#45;veclip"}
tags: ['Efficiency And Optimization', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
Large45;scale web45;crawled datasets are fundamental for the success of pre45;training vision45;language models such as CLIP. However the inherent noise and potential irrelevance of web45;crawled AltTexts pose challenges in achieving precise image45;text alignment. Existing methods utilizing large language models (LLMs) for caption rewriting have shown promise on small curated datasets like CC3M and CC12M. This study introduces a scalable pipeline for noisy caption rewriting. Unlike recent LLM rewriting techniques we emphasize the incorporation of visual concepts into captions termed as Visual45;enriched Captions (VeCap). To ensure data diversity we propose a novel mixed training scheme that optimizes the utilization of AltTexts alongside newly generated VeCap. We showcase the adaptation of this method for training CLIP on large45;scale web45;crawled datasets termed VeCLIP. Employing this cost45;effective pipeline we effortlessly scale our dataset up to 300 million samples named VeCap dataset. Our results show significant advantages in image45;text alignment and overall model performance. For example VeCLIP achieves up to +25.237; gain in COCO and Flickr30k retrieval tasks under the 12M setting. For data efficiency VeCLIP achieves +337; gain while only using 1437; of the data employed in the vanilla CLIP and 1137; in ALIGN. We also note the VeCap data is complementary with other well curated datasets good for zero45;shot classification tasks. When combining VeCap and DFN our model can achieve strong performance on both of image45;text retrieval and zero45;shot classification tasks e.g. 83.137; accuracy35;64;1 on ImageNet zero45;shot for a H/14 model. We release the pre45;trained models at https://github.com/apple/ml&#45;veclip.
