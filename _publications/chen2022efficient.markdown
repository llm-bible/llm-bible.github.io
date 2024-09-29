---
layout: publication
title: Litevl Efficient Video45;language Learning With Enhanced Spatial45;temporal Modeling
authors: Chen Dongsheng, Tao Chaofan, Hou Lu, Shang Lifeng, Jiang Xin, Liu Qun
conference: "Arxiv"
year: 2022
bibkey: chen2022efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.11929"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
Recent large45;scale video45;language pre45;trained models have shown appealing performance on various downstream tasks. However the pre45;training process is computationally expensive due to the requirement of millions of video45;text pairs and the redundant data structure of each video. To mitigate these problems we propose LiteVL which adapts a pre45;trained image45;language model BLIP into a video45;text model directly on downstream tasks without heavy pre45;training. To enhance the temporal modeling lacking in the image45;language model we propose to add temporal attention modules in the image encoder of BLIP with dynamic temporal scaling. Besides the model45;wise adaptation we also propose a non45;parametric pooling mechanism to adaptively reweight the fine45;grained video embedding conditioned on the text. Experimental results on text45;video retrieval and video question answering show that the proposed LiteVL even outperforms previous video45;language pre45;trained models by a clear margin though without any video45;language pre45;training.
