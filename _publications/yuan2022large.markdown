---
layout: publication
title: Wudaomm A Large45;scale Multi45;modal Dataset For Pre45;training Models
authors: Yuan Sha, Zhao Shuai, Leng Jiahong, Xue Zhao, Zhao Hanyu, Liu Peiyu, Gong Zheng, Zhao Wayne Xin, Li Junyi, Tang Jie
conference: "Arxiv"
year: 2022
bibkey: yuan2022large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.11480"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Compared with the domain45;specific model the vision45;language pre45;training models (VLPMs) have shown superior performance on downstream tasks with fast fine45;tuning process. For example ERNIE45;ViL Oscar and UNIMO trained VLPMs with a uniform transformers stack architecture and large amounts of image45;text paired data achieving remarkable results on downstream tasks such as image45;text reference(IR and TR) vision question answering (VQA) and image captioning (IC) etc. During the training phase VLPMs are always fed with a combination of multiple public datasets to meet the demand of large45;scare training data. However due to the unevenness of data distribution including size task type and quality using the mixture of multiple datasets for model training can be problematic. In this work we introduce a large45;scale multi45;modal corpora named WuDaoMM totally containing more than 650M image45;text pairs. Specifically about 600 million pairs of data are collected from multiple webpages in which image and caption present weak correlation and the other 50 million strong45;related image45;text pairs are collected from some high45;quality graphic websites. We also release a base version of WuDaoMM with 5 million strong45;correlated image45;text pairs which is sufficient to support the common cross45;modal model pre45;training. Besides we trained both an understanding and a generation vision45;language (VL) model to test the dataset effectiveness. The results show that WuDaoMM can be applied as an efficient dataset for VLPMs especially for the model in text45;to45;image generation task. The data is released at https://data.wudaoai.cn
