---
layout: publication
title: Litevl: Efficient Video-language Learning With Enhanced Spatial-temporal Modeling
authors: Chen Dongsheng, Tao Chaofan, Hou Lu, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2022
bibkey: chen2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.11929"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Recent large-scale video-language pre-trained models have shown appealing performance on various downstream tasks. However the pre-training process is computationally expensive due to the requirement of millions of video-text pairs and the redundant data structure of each video. To mitigate these problems we propose LiteVL which adapts a pre-trained image-language model BLIP into a video-text model directly on downstream tasks without heavy pre-training. To enhance the temporal modeling lacking in the image-language model we propose to add temporal attention modules in the image encoder of BLIP with dynamic temporal scaling. Besides the model-wise adaptation we also propose a non-parametric pooling mechanism to adaptively reweight the fine-grained video embedding conditioned on the text. Experimental results on text-video retrieval and video question answering show that the proposed LiteVL even outperforms previous video-language pre-trained models by a clear margin though without any video-language pre-training.
