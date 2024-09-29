---
layout: publication
title: Image Captioning With Deep Bidirectional Lstms
authors: Wang Cheng, Yang Haojin, Bartz Christian, Meinel Christoph
conference: "Arxiv"
year: 2016
bibkey: wang2016image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1604.00790"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
This work presents an end45;to45;end trainable deep bidirectional LSTM (Long45;Short Term Memory) model for image captioning. Our model builds on a deep convolutional neural network (CNN) and two separate LSTM networks. It is capable of learning long term visual45;language interactions by making use of history and future context information at high level semantic space. Two novel deep bidirectional variant models in which we increase the depth of nonlinearity transition in different way are proposed to learn hierarchical visual45;language embeddings. Data augmentation techniques such as multi45;crop multi45;scale and vertical mirror are proposed to prevent overfitting in training deep models. We visualize the evolution of bidirectional LSTM internal states over time and qualitatively analyze how our models translate image to sentence. Our proposed models are evaluated on caption generation and image45;sentence retrieval tasks with three benchmark datasets Flickr8K Flickr30K and MSCOCO datasets. We demonstrate that bidirectional LSTM models achieve highly competitive performance to the state45;of45;the45;art results on caption generation even without integrating additional mechanism (e.g. object detection attention model etc.) and significantly outperform recent methods on retrieval task.
